<template>
    <v-card>
      <v-tabs
        fixed-tabs
        background-color="blue-grey darken-4"
        center-active
        dark
        >
        <v-tab> <h2 class="font-weight-medium">Dados pessoais</h2> </v-tab>
        <v-tab> <h2 class="font-weight-medium">Experiências</h2> </v-tab>
        <v-tab> <h2 class="font-weight-medium">Formação acadêmica</h2> </v-tab>
      </v-tabs>
    </v-card>
</template>

<script>
  export default {
    name: 'Menu'
  }
</script>