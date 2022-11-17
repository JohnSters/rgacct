<template>
  <v-container>
    <v-card class="landing hidden-sm-and-down pa-8" shaped>
      <v-img class="ma-auto" src="/logo/logo.svg" width="300"></v-img>
      <p class="mt-8 text-center"><b class="green--text">Contact:</b> Christo Thompson</p>
      <p class="text-center"><b class="green--text">Tel:</b> +27 72 501 5014</p>
      <p class="text-center"><b class="green--text">email:</b> christo@rgacct.co.za
        <v-tooltip bottom>
          <template v-slot:activator="{ on, attrs }">
              <v-icon
                @click="clipboard"
                color="primary"
                class="ml-1 mb-1"
                dark
                v-bind="attrs"
                v-on="on"
              >
                mdi-paperclip
              </v-icon>
          </template>
          <span>Copy to Clipboard</span>
        </v-tooltip>
      </p>
    </v-card>
    <v-card class="landing-mb hidden-md-and-up" flat>
      <v-img class="ma-auto" src="/logo/logo.svg" width="300"></v-img>
      <p class="mt-8 text-center"><b class="green--text">Contact:</b>
        Christo Thompson
      </p>
      <p class="text-center"><b class="green--text">Tel:</b> +27 72 501 5014</p>
      <p class="text-center"><b class="green--text">email:</b> christo@rgacct.co.za
        <v-tooltip bottom>
          <template v-slot:activator="{ on, attrs }">
            <v-icon
              @click="clipboard"
              color="primary"
              class="ml-1 mb-1"
              dark
              v-bind="attrs"
              v-on="on"
            >
              mdi-paperclip
            </v-icon>
          </template>
          <span>Copy to Clipboard</span>
        </v-tooltip>
      </p>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: 'ContactUs',
  data: () => ({}),

  methods: {
    clipboard () {
      const email = 'christo@rgacct.co.za'
      navigator.clipboard.writeText(email)
    }
  }
}
</script>

<style scoped>
.landing {
  margin-top: 18%;
}

.landing-mb {
  margin-top: 60%;
}
</style>
