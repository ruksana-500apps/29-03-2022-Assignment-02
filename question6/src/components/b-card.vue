<template>
  <div>
    <b-card>
      <b-card-text v-for="data1 in data" :key='data1.id'>
         name:{{data1.name}}
         Description:{{data1.description}}
      </b-card-text>
    </b-card>
  </div>
</template>


<script>
export default {
  data()
  {
    return {
      data : [{ "name" :" Agile CRM" , "description" :" A company of excellence"}, 
      {"name":"mantra technologies", "description":"500apps" },
      {"name":"500apps Python", "description":"Backend built using python" },
      {"name":"500apps infinity", "description":"Builtusing vue JS" }]
    }
  }
}
</script>
