<template>
  <v-container grid-list-xs>
    
  
    <RewardsTable />
    
  </v-container>
</template>

<script>
  
  import RewardsTable from '../components/RewardsTable'
  

  export default {
    name: 'RewardsView',

    components: {
      RewardsTable,
      
    },
  }
</script>
