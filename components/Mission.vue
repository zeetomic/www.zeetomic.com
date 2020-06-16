<template>
  <div class="network_nest">
    <v-row data-aos="fade-right" data-aos-duration="3000"> 
      <v-col cols="12" xs="12" sm="12" md="6" lg="6" xl="6" style="text-align: end">
        <p class="font-weight-bold display-2">Mission</p>
        <p class="font-weight-regular subtitle-1" style="font-size:18px">Fast, simple and cost reduction for security/utility token issuing platform.</p>
      </v-col>
    </v-row>
    <v-row class="d-flex align-center justify-center">
      <img src="~/assets/netnest.png" alt="netnest" class="netnest">
    </v-row>
    <v-row data-aos="fade-left" data-aos-duration="3000">
      <v-col></v-col>
      <v-col cols="12" xs="12" sm="12" md="6" lg="6" xl="6">
        <p class="font-weight-bold display-2">Vision</p>
        <p class="font-weight-regular subtitle-1">Zeetomic is a bridge of blockchain with a single and simple endpoint integration that empowers all classes of the business ecosystem.</p>
      </v-col>
    </v-row>
  </div>
</template>

<style scoped>
.netnest {
  position: absolute;
  width: 30%;
  animation: rotate-s-loader 40s linear infinite;
}
@keyframes rotate-s-loader {
  from {
    transform: rotate(0);
  }
  to {
    transform: rotate(360deg);
  }
}
.network_nest {
  background-image: url('../assets/zee-header-banner.jpg');
  background-repeat: no-repeat;
  background-position: center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  padding: 5rem 12rem;
}
@media screen and (min-width: 1265px) and (max-width: 1919px) {
  .netnest {
    width: 25%;
  }
}
@media screen and (min-width: 1920px) {
  .netnest {
    width: 20%;
  }
}
</style>