<template>
    <v-card
    class="flex"
    color="grey darken-4"
    flat
    tile>
        <v-card-text
        class="py-2 white--text text-right"
        color="black">
            {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
        </v-card-text>
    </v-card>
</template>

<script>
  export default {
    name: 'Loginbar'
  }
</script>