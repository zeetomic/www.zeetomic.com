<template>
<div class="main">
  <div class="successful">
    <v-row align="center" justify="center">
      <v-card light class="pa-10" width="500">
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
  </div>
</div>
</template>

<script>
export default {
  layout: ({ isMobile }) => isMobile ? 'mobile' : 'default',
  head () {
    return {
      title: 'Failed Verification',
    }
  },
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
</style>