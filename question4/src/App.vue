<template>
  
  <data1 :sname="sname"></data1>

</template>

<script>

import data1 from './components/PropssData.vue'


export default {
  name: 'App',
  components: {
    data1
  },

    data(){
      return{
        sname : "Mantra"
      }
    }
  };
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
