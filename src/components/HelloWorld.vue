<template>
  <div id="app">
    {{ message }}
  </div>
</template>

<script>
import Vue from 'vue'
var app = new Vue({
  el: '#app',
  data: {
    message: 'Hello Vue!'
  }
})
Vue.use({
  app
})
</script>
