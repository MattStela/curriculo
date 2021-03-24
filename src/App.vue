<template>
  <v-app>
    <v-main style="background-color: black">
      <v-container>

        <Info />
        <!-- If using vue-router -->
        <router-view></router-view>
      </v-container>
      <Footer />
    </v-main>
  </v-app>
</template>

<script>
import Footer from "./components/Footer";
import Info from "./components/Info";

export default {
  name: "App",

  components: {
    Footer,
    Info,
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