<template>
  <div id="app">
    <nav-bar />
    <nuxt />
  </div>
</template>
<script>
import NavBar from '~/components/NavBar.vue'
export default {
  components: {
    NavBar
  }
}
</script>

<style>
html {
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
  font-family: 'Open Sans', sans-serif;
  font-size: 16px;
  line-height: 1.15;
}
h1 {
  font-size: 50px;
  font-weight: 700px;
}
</style>
