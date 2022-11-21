<template>
  <v-container>
    <v-card class="ma-auto hidden-sm-and-down text-center" flat>
      <v-img class="mt-12" src="/logo/logo.svg" height="400" contain></v-img>
      <v-img src="/plant.png" class="plant ml-n4 hidden-sm-and-down" width="180" contain></v-img>
    </v-card>
    <v-card class="ma-auto hidden-md-and-up text-center" flat>
      <v-img src="/logo/logo.svg" height="350" contain></v-img>
      <v-img src="/plant.png" class="ml-n8 hidden-md-and-up" width="130" contain></v-img>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style>
.plant {
  position:fixed;
  bottom: 50px;
  left: 0;
}
</style>
