<template>
  <div id="app">
    <comp name=mantra mail=mantra@500apps.com></comp>
  </div>
</template>

<script>
import comp from './src/components/CompData.vue'
export default {
  name: 'App',
  //component register
  components: {
    comp
   
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
