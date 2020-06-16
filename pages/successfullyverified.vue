<template>
<div class="main">
  <div class="successful">
    <v-row align="center" justify="center">
      <v-card light class="pa-10" width="500">
        <v-row justify="center">
          <img class="correct" src="../assets/correct.svg" alt="correct">
        </v-row>
        <p class="text-center font-weight-bold regular">User Successfully Activated</p>
        <p class="text-center">Congratulations your user successfully activated. Please login to perform other operations.</p>
        <v-row justify="center">
          <v-btn color="#00b5ad" href="https://wallet.zeetomic.com/login">Go To The Platform</v-btn>
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
      title: 'Successfully Verified',
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