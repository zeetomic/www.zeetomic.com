<template>
  <div>
    <div class="main">
      <Header />
      <div class="successful">
        <v-row>
          <v-col>
            <v-row align="center" justify="center">
              <v-card class="pa-10" width="500">
                <v-row justify="center">
                  <img class="correct" src="../assets/incorrect.svg" alt="correct">
                </v-row>
                <p class="text-center font-weight-bold regular">User Verification Failed</p>
                <p class="text-center">The user verification was not successful. Please contact our support at support@zeetomic.com</p>
                <v-row justify="center">
                  <v-btn color="#00b5ad" nuxt to="/">Go Back</v-btn>
                </v-row>
              </v-card>
            </v-row>
          </v-col>
        </v-row>
      </div>
    </div>
  </div>
</template>

<script>
import Footer from '~/components/Footer.vue';
import Header from '~/components/Header.vue';
export default {
  components: {
    Header,
    Footer
  }
}
</script>

<style scoped>
.main {
  background: #012639;
}
.successful {
  padding: 10rem 0rem;
}
.correct {
  width: 8rem
}

@media screen and (max-width: 600px) {
 .successful {
   padding: 4rem 2rem;
 }
}
/* @media screen and (min-width: 601px) and (max-width: 920px) {
 
}
@media screen and (min-width: 921px) and (max-width: 1264px) {
  
}
@media screen and (min-width: 1265px) and (max-width: 1904px) {
 
} */
</style>