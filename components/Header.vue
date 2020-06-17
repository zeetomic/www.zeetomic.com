<template>
  <v-app-bar
    absolute
    flat
    color="transparent"
    class="header"
  >
    <v-btn color="transparent" text nuxt to="/">
      <v-img :src="zeetomic" max-width="170px"></v-img>
    </v-btn>
    <v-spacer></v-spacer>
    <v-menu
      v-model="menu"
      :close-on-content-click="false"
      :nudge-width="200"
      offset-y
      open-on-hover
      light
    >
      <template v-slot:activator="{ on }">
        <v-btn
          color="white--text font-weight-bold"
          large
          dark
          text
          v-on="on"
        >
          Products 
          <v-icon small>fas fa-chevron-down</v-icon>
        </v-btn>
      </template>
      <v-card class="pa-6" width="600px">
        <v-row>
          <v-col>
            <div class="pl-2">
              <p class="font-weight-bold">For Everyone</p>
              <div class="pt-2"></div>
              <v-btn text href="https://wallet.zeetomic.com/" target="blank">
                <v-img :src="z_logo" max-width="28px"></v-img>
                <span>Zeetomic Wallet</span>
              </v-btn>
              <br>
              <span class="grey--text caption pl-4">Store your own digital asset</span>
            </div>
          </v-col>
          <v-col>
            <p class="font-weight-bold">For Businesses</p>
            <div class="pl-4 pt-2">
              <span class="grey--text caption">Customer loyalty</span>
              <br><span class="grey--text caption">Vested shares</span>
              <br><span class="grey--text caption">Payment</span>
            </div>
          </v-col>
        </v-row>
      </v-card>
    </v-menu>
    <v-btn text large class="white--text font-weight-bold" nuxt to="/about">About</v-btn>
    <v-btn text large class="white--text font-weight-bold" nuxt to="/blog">Blog</v-btn>
    <v-spacer></v-spacer>
    <v-btn text large class="white--text font-weight-bold" href="https://wallet.zeetomic.com/login">Log In</v-btn>
    <v-btn outlined class="white--text font-weight-bold" href="https://wallet.zeetomic.com/login">Sign Up</v-btn>
  </v-app-bar>
</template>

<script>
export default {
  data() {
    return {
      menu: false,

      zeetomic: require('~/assets/zeetomic-logo-header.png'),
      z_logo: require('~/assets/z-logo-copy.png')
    }
  }
}
</script>

<style scoped>
.header {
  padding: 0 10%!important;
}
</style>