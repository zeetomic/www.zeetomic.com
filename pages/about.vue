<template>
<div>
  <div class="main">
    <div style="padding: 6rem 12%; text-align: start">
      <v-row>
        <v-col cols="12" xs="12" sm="12" md="" lg="" xl="">
          <p class="display-2">ABOUT</p>
        </v-col>
        <v-col>
          <p style="font-size: 18px">Zeetomic is a new generation of trusted global solutions for creating a digital asset. Customer Loyalty, Real Estate, Vested Shares and Payment Solution based on blockchain.</p>
          <v-divider></v-divider>
          <p style="font-size: 18px">The platform is designed to bring collectively a set of logistics, private equity, food, and hospitality transaction more efficiency. We have built a risk-free infrastructure established for security/utility token offerings on Zeetomic to maximize the safety and security of transactions on the Platform.</p>
          <br>
          <p style="font-size: 18px">Zeetomic Platform currently built on top of the Stellar network and engages with advanced blockchain technology to extended capabilities as fast transaction processing at low cost, enhanced the security of all processes-from issuance to storage to transfers of tokens for swap, trading on the market.</p>
        </v-col>
      </v-row>
    </div>
  </div>
  <Mission />
  <div class="team">
    <p class="text-center font-weight-bold white--text" style="font-size: 48px">OUR TEAM</p>
    <v-row>
      <v-col cols="12" xl="4" lg="4" md="4" sm="" xs="">
        <v-hover v-slot:default="{ hover }">
          <v-card :elevation="hover ? 10 : 2" class="px-6 pt-4 card-img">
            <v-row justify="center">
              <img src="../assets/bro-3.jpg">
            </v-row>
            <div class="text-center py-2">
              <span class="font-weight-bold grey--text" style="font-size:20px">Saing Sab</span>
              <p class="grey--text">Co-Founder</p>
            </div>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" xl="4" lg="4" md="4" sm="" xs="">
        <v-hover v-slot:default={hover}>
          <v-card :elevation="hover ? 10 : 2" class="px-6 pt-4 card-img">
            <v-row justify="center">
              <img src="../assets/bro-2.jpg">
            </v-row>
            <div class="text-center py-2">
              <span class="font-weight-bold grey--text" style="font-size:20px">Thul Rithy</span>
              <p class="grey--text">Advisor</p>
            </div>
          </v-card> 
        </v-hover>
      </v-col>
      <v-col cols="12" xl="4" lg="4" md="4" sm="" xs="">
        <v-hover v-slot:default={hover}>
          <v-card :elevation="hover ? 10 : 2" class="px-6 pt-4 card-img">
            <v-row justify="center">
              <img src="../assets/bro-4.jpg">
            </v-row>
            <div class="text-center py-2">
              <span class="font-weight-bold grey--text" style="font-size:20px">Sokhomoliyuth Tea</span>
              <p class="grey--text">Technial Advisor</p>
            </div>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" xl="4" lg="4" md="4" sm="" xs="">
        <v-hover v-slot:default={hover}>
          <v-card :elevation="hover ? 10 : 2" class="px-6 pt-4 card-img">
            <v-row justify="center">
              <img src="../assets/bro-5.jpg">
            </v-row>
            <div class="text-center py-2">
              <span class="font-weight-bold grey--text" style="font-size:20px">Daveat Corn</span>
              <p class="grey--text">Mobile Developer</p>
            </div>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" xl="4" lg="4" md="4" sm="" xs="">
        <v-hover v-slot:default={hover}>
          <v-card :elevation="hover ? 10 : 2" class="px-6 pt-4 card-img">
            <v-row justify="center">
              <img src="../assets/bro-6.jpg">
            </v-row>
            <div class="text-center py-2">
              <span class="font-weight-bold grey--text" style="font-size:20px">Piset Heang</span>
              <p class="grey--text">Web Developer</p>
            </div>
          </v-card>
        </v-hover>
      </v-col>
    </v-row>
  </div>
</div>
</template>

<script>
import Mission from '~/components/Mission.vue';

export default {
  layout: ({ isMobile }) => isMobile ? 'mobile' : 'default',
  components: {
    Mission
  }
}
</script>

<style scoped>
.main {
  background-image: url('../assets/about.png');
  background-repeat: no-repeat;
  background-position: center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
.team {
  padding: 2.5rem 12rem;
  background-image: url('../assets/team.png');
  background-repeat: no-repeat;
  background-position: center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
.team img {
  width: 150px;
  height: 150px;
  border-radius: 50%!important;
}
.card-img {
  background: rgba(0, 0, 0, 0.2)!important;
}

@media screen and (max-width: 600px) {
  .network_nest {
    padding: 5rem 2rem;
  }
  .team {
    padding: 2.5rem 2rem;
  }
}
</style>