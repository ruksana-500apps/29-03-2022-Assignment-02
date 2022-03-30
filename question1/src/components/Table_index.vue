<template>
  <div>
    <center><table>
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Index</th>
                </tr>
            </thead>
            <tbody>
                <tr v-for="data in table_data" :key="data.id">
                   <td>{{data.name}} </td>
                   <td>{{data.index}}</td>
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
                  { "name" :" Agile CRM" ,'index':'0', "description" :" A company of excellence"}, 
                  {"name":"mantra technologies", 'index':'1',"description":"500apps" },
                  {"name":"500apps Python", 'index':'2',"description":"Backend built using python" },
                  {"name":"500apps infinity", 'index':'3',"description":"Builtusing vue JS" }
                  ]


    };
  }
 };
</script>

<style scoped>
table,td,th{
   border:1px solid;
}
</style>