<template>
  <div>
    <center><table>
            <tbody>
                <tr v-for="data in table_data" :key="data.id">
                    <td>Name :{{data.name}}</td></tr>
                <tr v-for="data in table_data" :key="data.id">
                    <td>Description : {{data.description}}</td>
                </tr>
                <tr v-for="data in table_data" :key="data.id">
                    <td>Year_Of_Experience :{{data.year_of_experience}}</td>
                </tr>
                <tr v-for="data in table_data" :key="data.id">
                    <td>Location :{{data.location}}</td>
                </tr>
                
            </tbody>
        </table></center>
  </div>
</template>



<script>
export default {
    name:"displayData",
    data()
    {
        return{
            table_data:[{
                "name":"Agile CRM",
                "description" : "A company of excellence",
                "year_of_experience" : 12,
                "location" : "Hyderabad"
            }]
        }
    }
}


</script>
