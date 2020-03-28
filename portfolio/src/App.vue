<template>
<div>
  <div id='app'>
    <NavBar></NavBar>
    <home-page></home-page>
    <Footer></Footer>
  </div>
</div>
</template>

<script>
import NavBar from './components/nav-bar.vue'
import HomePage from './components/HomePage.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    HomePage,
    Footer
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

}
</style>
