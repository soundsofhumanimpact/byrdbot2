<template>
  <div id="app">
    <SoundsOfImpact/>
  </div>
</template>

<script>
import SoundsOfImpact from './components/SoundsOfImpact.vue'

export default {
  name: 'App',
  components: {
    SoundsOfImpact, 
  }, 
}
</script>

<style>
html {
background-color: black; 
color: white; 
overflow: hidden; 
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  margin-top: 60px;
}
</style>
