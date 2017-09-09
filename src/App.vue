<template>
  <div id="app">
  	<navbar></navbar>
    <router-view></router-view>
    <footerbar></footerbar>
  </div>
</template>

<script>
import Navbar from './components/layouts/Navbar.vue'
import FooterBar from './components/layouts/FooterBar.vue'
export default {
  components: {
    navbar: Navbar,
    footerbar: FooterBar
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
