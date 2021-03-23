<template>
  <v-app>
    <v-main>
      <Menu/>
    <v-container fluid>
        <v-container>
            <template>
              <div>

                <v-avatar size="150" color="black" class="mt-n0 mx-auto">
                  <img src="https://cdn.vuetifyjs.com/images/john.jpg" alt="Matts">
                </v-avatar>

                <v-card
                class="mt-n12 mx-auto"
                elevation="20"
                height="460"
                max-width="800"
                color="WHITE"
                text-align="center">

                <h1 class="ophk">Matheus Alves Stela</h1>
                <h2 class="ophk">26 anos</h2>
                <h2 class="ophk">matheus.alves.stela@gmail.com</h2>
                <h2 class="ophk">São paulo - SP</h2>

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

<style>
.ophk{
  margin-left:80px
}
</style>