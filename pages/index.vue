<template>
  <v-container>
    <v-card class="landing hidden-sm-and-down" flat>
      <v-img src="/logo/logo.svg"></v-img>
      <p class="blue-grey--text display-1 text-center mt-8">"Trust is earned when actions meets words"</p>
    </v-card>
    <v-card class="landing-mb hidden-md-and-up" flat>
      <v-img src="/logo/logo.svg"></v-img>
      <p class="blue-grey--text  text-center mt-3">"Trust is earned when actions meets words"</p>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style>
.landing {
  margin-top: 13%;
}

.landing-mb {
  margin-top: 60%;
}
</style>
