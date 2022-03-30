<template>
<div>
  

  <h1>{{ msg }}</h1>

<childFile @emit-name="setmsg" ></childFile>
</div>
</template>
<script>
import childFile from "../src/components/ChildFile.vue"
export default{
name:'App',
components: {
    childFile,
},
data()
{
   return{
     msg:"Mantra"
         }
},
methods:{
    setmsg(pay)
    {
      this.msg=pay.msg;
    },
}
}
</script>
<style></style>