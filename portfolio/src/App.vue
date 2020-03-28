<template>
<div>
  <div id='app'>
    <NavBar></NavBar>
    <home-page></home-page>
  </div>
</div>
</template>

<script>
import NavBar from './components/nav-bar.vue'
import HomePage from './components/HomePage.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    HomePage,
    //HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
