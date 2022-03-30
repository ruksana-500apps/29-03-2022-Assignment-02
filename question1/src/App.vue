<template>
  <div id="app">
  <tableindex/>
  </div>
</template>

<script>
import tableindex from '../src/components/table_index.vue'

export default {
  name: 'App',
  components: {
    tableindex
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
