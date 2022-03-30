<template>
  <button  @click='emitCustomEvent'> Update me</button>
</template>

<script>
export default {
  name:'ChildFile',
  methods:{
    emitCustomEvent()
    {
      this.$emit('emit-name',{msg:'Ruksana'})
    }
  }
}
</script>

<style lang="css" scoped>
</style>