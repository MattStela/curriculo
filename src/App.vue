<template>
  <v-app>
    <v-main style="background-color: black">
      <Loginbar />
      <Menu />
      <v-container>
        <div style="margin-top: 5%">
          <!-- Avatar da página principal -->
          <Avatar />
        </div>
        
        <v-card
          style="height: 400px; margin: 2% 5% 0% 0%"
          color="blue-grey darken-4"
          
        >

          <v-container>
            <v-card
              color="blue-grey darken-3"
              style="height: 340px; margin: -10% -10% 0% 20%"
            >
              <!-- Conteúdo da página -->
              <v-container>
                <v-container>
                  <h1 class="font-weight-medium white--text">
                    matheus.alves.stela@gmail.com<br />
                    <br/>
                    (11) 94968-3673<br />
                    26 anos<br />
                    São Paulo - SP<br />
                    Bairro: Itaquera
                  </h1>
                </v-container>
              </v-container>
            </v-card>
          </v-container>
        </v-card>

        <!-- If using vue-router -->
        <router-view></router-view>
      </v-container>
      <Footer />
    </v-main>
  </v-app>
</template>

<script>
import Footer from "./components/Footer";
import Menu from "./components/Menu";
import Loginbar from "./components/Loginbar";
import Avatar from "./components/Avatar";

export default {
  name: "App",

  components: {
    Menu,
    Footer,
    Loginbar,
    Avatar,
  },

  data: () => ({
    //
  }),
};
</script>

<style>
.ophk {
  margin-left: 80px;
}
</style>