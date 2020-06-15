<template>
  <v-app id="app">
    <Navbar />
    <nuxt/>
    <MobileFooter />
  </v-app>
</template>

<script>
import Navbar from '~/components/Navbar.vue';
import MobileFooter from '~/components/MobileFooter.vue';
export default {
  components: {
    Navbar,
    MobileFooter
  }
}
</script>

<style>
  @media only screen and (max-width: 500px) {
    #app .display-2 {
      font-size: 36px!important;
    }
    #app .display-1 {
      font-size: 26px!important;
    }
    #app .title {
      font-size: 16px!important;
    }
  }
  /* Tablet */
  @media only screen and (min-width: 501px) and (max-width: 768px) {
      
  }
</style>