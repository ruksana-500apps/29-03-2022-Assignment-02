<template>
  <div id="app">
    <data1/>
  </div>
</template>

<script>
import data1 from './components/Display-data.vue'

export default {
  name: 'App',
  components:{
    data1
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
