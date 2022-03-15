<template>
  <v-container grid-list-xs>
    
  
    <PlansTable />
    
  </v-container>
</template>

<script>
  
  import PlansTable from '../components/PlansTable'
  

  export default {
    name: 'PlansView',

    components: {
      PlansTable,
      
    },
  }
</script>
