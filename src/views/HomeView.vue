<template>
  <v-container grid-list-xs>
    
  
    <PlansList />
    <v-divider></v-divider>
    <RewardsList />
  </v-container>
</template>

<script>
  
  import PlansList from '../components/PlansList'
  import RewardsList from '../components/RewardsList'

  export default {
    name: 'Home',

    components: {
      PlansList,
      RewardsList
    },
  }
</script>
