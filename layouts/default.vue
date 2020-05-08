<template>
  <v-app>
    <nuxt />
    <Footer />
  </v-app>
</template>

<script>
import Footer from '~/components/Footer.vue';
export default {
  components: {
    Footer
  }
}
</script>

<style lang="scss">
 *,
  *:before,
  *:after {
    margin: 0;
  }
  .v-application {
    font-family: 'Montserrat'!important;
  }
  .semi-bold {
    font-size: 48px;
  }
  .regular {
    font-size: 21px;
  }
  @media screen and (max-width: 600px) {
    .section1 {
      padding: 1rem 3rem!important;
    }
    
    .semi-bold {
      font-size: 24px!important;
    }
    .regular {
      font-size: 16px;
    }
    .carousel_detail {
      padding: 0!important;
    }
  }
  @media screen and (min-width: 601px) and (max-width: 920px) {
    .step1_img{
      width: 250px!important;
    }
    .semi-bold {
      font-size: 38px!important;
    }
    .carousel_detail {
      padding: 0 1rem!important;
    }
  }
  @media screen and (min-width: 921px) and (max-width: 1264px) {
    .semi-bold {
      font-size: 38px!important;
    }
  }
  @media screen and (min-width: 1265px) and (max-width: 1904px) {
    
  }
</style>