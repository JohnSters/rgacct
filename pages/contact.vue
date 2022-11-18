<template>
  <v-container>
    <v-card class="landing hidden-sm-and-down pa-8 mt-lg-16" shaped>
      <v-img class="ma-auto mt-6 mb-3" src="/christo.png" width="200"></v-img>
      <p class="mt-8 text-center"><b class="green--text"></b> Christo Thompson</p>
      <p class="text-center">Professional Accountant (SA) / Professional Tax Practitioner (SA)</p>
      <p class="text-center">Specializes in Tax and accounting services for small and medium enterprises mainly in the agricultural
        sector from 2009. Very passionate Show budgie breeder since 2012. Current BSSA Treasurer.</p>
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
    <div class="hidden-md-and-up">
      <v-img class="ma-auto mt-6 mb-3" src="/christo.png" width="150" contain></v-img>
      <p class="mt-8 text-center"><b class="green--text"></b> Christo Thompson</p>
      <p class="text-center">Professional Accountant (SA) / Professional Tax Practitioner (SA)</p>
      <p class="text-center">Specializes in Tax and accounting services for small and medium enterprises mainly in the agricultural
        sector from 2009. Very passionate Show budgie breeder since 2012. Current BSSA Treasurer.</p>
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
    </div>
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
</style>
