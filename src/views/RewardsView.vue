2<template>
  <v-container grid-list-xs>
    
  
    <RewardsList />
    
  </v-container>
</template>

<script>
  
  import RewardsList from '../components/RewardsList'
  

  export default {
    name: 'RewardsView',

    components: {
      RewardsList,
      
    },
  }
</script>
