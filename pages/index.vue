<template>
  <v-container>
    <v-card class="ma-auto hidden-sm-and-down text-center" height="400" flat>
      <v-img src="/logo/logo.svg" height="400" contain></v-img>
    </v-card>
    <v-card class="ma-auto hidden-md-and-up text-center" height="200" flat>
      <v-img src="/logo/logo.svg" height="200" contain></v-img>
      <v-img src="/plant.png" class="ml-n8 hidden-md-and-up" style="margin-bottom: 55px" width="150" contain></v-img>
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
}
</style>
