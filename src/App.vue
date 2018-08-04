<template>
  <div id=#app>
    <app-header></app-header>
    <app-nav></app-nav>
  </div>
  
</template>

<script>
import Header from './components/Header.vue'
import Navbar from './components/Navbar.vue'

export default {
  components: {
    appHeader: Header,
    appNav: Navbar
  }
}
</script>

<style>
body {
  margin: 0;
  display: grid;
}
#app {
  display: grid;
  background-color: red;
  margin: 0%;
}
</style>




