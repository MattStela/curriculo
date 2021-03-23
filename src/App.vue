<template>
  <v-app>
    <v-main>
      <Menu/>
      <v-container fluid>
        <v-container>
<template>
  <div>
    <v-avatar
    color="primary"
    size="128"
    
    ></v-avatar>
    
   

    <v-card
      class="mt-n12 mx-auto"
      elevation="12"
      height="200"
      max-width="300"
      color="secondary"
    >
    
    </v-card>

  </div>
</template>
        </v-container>
      <!-- If using vue-router -->
      <router-view></router-view>

    </v-container>
      <Footer/>
    </v-main>
  </v-app>
</template>

<script>
import Footer from './components/Footer';
import Menu from './components/Menu';

export default {
  name: 'App',

  components: {
    Menu,
    Footer
  },

  data: () => ({
    //
  }),
};
</script>
