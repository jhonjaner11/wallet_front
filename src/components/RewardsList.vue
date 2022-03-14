<template>
  

    <div>
        <h1>Rewards:</h1>
        <v-item-group>
            <v-container>
            <v-row>
                <v-col
                v-for="n in rewards"
                :key="n.id"
                cols="12"
                md="4"
                >
                
                    <v-card
                    :color="active ? 'primary' : ''"
                    class="d-flex align-center"
                    dark
                    
                    @click="toggle"
                    >
                    <v-card-title primary-title>
                        {{n.name}}
                    </v-card-title>
                    <v-card-text>
                        <v-row>

                        </v-row>
                    </v-card-text>
                    
                                                                                                                                                                                                                                 
                    </v-card>
               
                </v-col>
            </v-row>
            </v-container>
        </v-item-group>
    </div>
</template>

<script>
  

  export default {
    name: 'Rewards',

        data: () => ({
        rewards : [
            {
                id: 1, 
                name: 'Reward 1', 
                duration: '1 day', 
                min: 100,
                max: 199,
                percentage: '10%'
            },
            {
                id: 2, 
                name: 'Reward 2', 
                duration: '2 day', 
                min: 200,
                max: 499,
                percentage: '15%'
            },
            {
                id: 3, 
                name: 'Reward 3', 
                duration: '3 day', 
                min: 500,
                max: 1000,
                percentage: '20%'
            }
        ]




    }),

    components: {
      
    },
  }
</script>
