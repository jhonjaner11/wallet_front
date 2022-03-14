<template>
  <v-container grid-list-xs>
    
  
    <PlansList />
    
  </v-container>
</template>

<script>
  
  import PlansList from '../components/PlansList'
  

  export default {
    name: 'PlansView',

    components: {
      PlansList,
      
    },
  }
</script>
