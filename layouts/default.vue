<template>
  <v-app dark>
    <v-app-bar
      fixed
      app
    >
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
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
