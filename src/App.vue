<template>    
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <LandingPage msg="Welcome to Your Vue.js App"/>

  
</template>

<script>
import LandingPage from './components/Landing.vue'

export default {
  name: 'App',
  components: {
    LandingPage
  }
}
</script>

<!-- <style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: rgb(239, 241, 243);
  margin-top: 60px;
}
</style> -->
