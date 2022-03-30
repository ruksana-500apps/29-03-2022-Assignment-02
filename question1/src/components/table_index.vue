<template>
  <div>
    <center><table>
            <thead>
                <tr>
                    <th>Name</th>
                </tr>
            </thead>
            <tbody>
                <tr v-for="data in table_data" :key="data.id">
                   <td>{{data.name}} </td>
                </tr>
            </tbody>
        </table></center>
  </div>
</template>
<script>
export default {
  name: 'tableData',
     data(){
         return{
              table_data : [
                  { "name" :" Agile CRM" , "description" :" A company of excellence"}, 
                  {"name":"mantra technologies", "description":"500apps" },
                  {"name":"500apps Python", "description":"Backend built using python" },
                  {"name":"500apps infinity", "description":"Builtusing vue JS" }
                  ]


    };
  }
 };
</script>

<style scoped>
table,td{
   border:2px solid;
}
</style>