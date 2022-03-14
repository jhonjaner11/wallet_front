<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
          transition="scale-transition"
          width="40"
        />
        <router-link to="/">      
      <v-btn
        target="_blank"
        text
      >
        <h2>Wallet</h2>
      </v-btn>
      </router-link>
        

        
      </div>

      <v-spacer></v-spacer>


      <router-link to="/plans">      
      <v-btn
        target="_blank"
        text
      >
        <span class="mr-2">Plans</span>
      </v-btn>
      </router-link>

      <router-link to="/rewards">      
        <v-btn
          target="_blank"
          text
        >
          <span class="mr-2">Rewards</span>
        </v-btn>
      </router-link>
     
      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Logout</span>
        <v-icon>open_in_new</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
