<template>
  <v-app>
    <v-app-bar
      color="white"
      fixed
      app
      flat
    >
      <v-btn to="/" class="blue-grey--text" rounded text>Home</v-btn>
      <v-btn to="/about" class="blue-grey--text" rounded text>About</v-btn>
      <v-btn to="/contact" class="blue-grey--text" rounded text>Contact</v-btn>
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
    <v-img src="/plant.png" class="ml-n4 hidden-md-and-up" style="margin-bottom: 55px" width="100" contain></v-img>
    <v-img src="/plant.png" class="ml-n4 hidden-sm-and-down" style="margin-bottom: 55px" width="200" contain></v-img>
    <v-footer fixed padless>
      <v-col
        class="text-center green white--text"
        cols="12"
      >
        {{ new Date().getFullYear() }} — <strong>Rising Green Accounting</strong>
      </v-col>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data () {
    return {}
  }
}
</script>

<style>

</style>
