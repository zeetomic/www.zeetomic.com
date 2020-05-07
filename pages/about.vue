<template>
  <div>
    <div class="main">
      <Header />
      <div style="padding: 5rem 12%">
        <v-row>
          <v-col cols="12" xs="12" sm="12" md="" lg="" xl="">
            <p class="font-weight-bold grey--text semi-bold">ABOUT</p>
          </v-col>
          <v-col>
            <p class="grey--text" style="font-size: 18px">Zeetomic is a new generation of trusted global solutions for creating a digital asset. Customer Loyalty, Real Estate, Vested Shares and Payment Solution based on blockchain.</p>
            <v-divider dark></v-divider>
            <p class="grey--text" style="font-size: 18px">The platform is designed to bring collectively a set of logistics, private equity, food, and hospitality transaction more efficiency. We have built a risk-free infrastructure established for security/utility token offerings on Zeetomic to maximize the safety and security of transactions on the Platform.</p>
            <br>
            <p class="grey--text" style="font-size: 18px">Zeetomic Platform currently built on top of the Stellar network and engages with advanced blockchain technology to extended capabilities as fast transaction processing at low cost, enhanced the security of all processes-from issuance to storage to transfers of tokens for swap, trading on the market.</p>
          </v-col>
        </v-row>
      </div>
    </div>
    <div class="network_nest">
      <v-row data-aos="fade-right" data-aos-duration="3000"> 
        <v-col cols="12" xs="12" sm="12" md="6" lg="6" xl="6" style="text-align: end">
          <p class="font-weight-bold semi-bold" style="color:#485865">Mission</p>
          <p class="font-weight-regular" style="font-size:18px; color:#444444">Fast, simple and cost reduction for security/utility token issuing platform.</p>
        </v-col>
      </v-row>
      <v-row data-aos="fade-left" data-aos-duration="3000">
        <v-col></v-col>
        <v-col cols="12" xs="12" sm="12" md="6" lg="6" xl="6">
          <p class="font-weight-bold semi-bold" style="color:#485865">Vision</p>
          <p class="font-weight-regular regular" style="color:#444444">Zeetomic is a bridge of blockchain with a single and simple endpoint integration that empowers all classes of the business ecosystem.</p>
        </v-col>
      </v-row>
    </div>
    <div class="our_team">
      <p class="text-center font-weight-bold grey--text" style="font-size: 48px">OUR TEAM</p>
      <v-row>
        <v-col>
          <v-row justify="center">
            <v-avatar size="150">
              <img
                src="../assets/bro-3.jpg"
                alt="John"
              >
            </v-avatar>
          </v-row>
          <div class="text-center" style="padding-top:1rem">
            <p class="font-weight-bold white--text" style="font-size:20px">Saing Sab</p>
            <p class="grey--text">Co-Founder</p>
          </div>
        </v-col>
        <v-col>
          <v-row justify="center">
            <v-avatar size="150">
              <img
                src="../assets/bro-2.jpg"
                alt="John"
              >
            </v-avatar>
          </v-row>
          <div class="text-center" style="padding-top:1rem">
            <p class="font-weight-bold white--text" style="font-size:20px">Thul Rithy</p>
            <p class="grey--text">Advisor</p>
          </div>
        </v-col>
        <v-col>
          <v-row justify="center">
            <v-avatar size="150">
              <img
                src="../assets/bro-4.jpg"
                alt="John"
              >
            </v-avatar>
          </v-row>
          <div class="text-center" style="padding-top:1rem">
            <p class="font-weight-bold white--text" style="font-size:20px">Sokhomoliyuth Tea</p>
            <p class="grey--text">Technial Advisor</p>
          </div>
        </v-col>
      </v-row>
      <v-row>
        <v-col>
          <v-row justify="center">
            <v-avatar size="150">
              <img
                src="../assets/bro-5.jpg"
                alt="John"
              >
            </v-avatar>
          </v-row>
          <div class="text-center" style="padding-top:1rem">
            <p class="font-weight-bold white--text" style="font-size:20px">Daveat Corn</p>
            <p class="grey--text">Mobile Developer</p>
          </div>
        </v-col>
        <v-col>
          <v-row justify="center">
            <v-avatar size="150">
              <img
                src="../assets/bro-6.jpg"
                alt="John"
              >
            </v-avatar>
          </v-row>
          <div class="text-center" style="padding-top:1rem">
            <p class="font-weight-bold white--text" style="font-size:20px">Heang Piset</p>
            <p class="grey--text">Web Developer</p>
          </div>
        </v-col>
        <v-col>
          <v-row justify="center">
            <v-avatar size="150">
              <img
                src="../assets/bro-7.jpg"
                alt="John"
              >
            </v-avatar>
          </v-row>
          <div class="text-center" style="padding-top:1rem">
            <p class="font-weight-bold white--text" style="font-size:20px">Chinyong Chhe</p>
            <p class="grey--text">Backend Developer</p>
          </div>
        </v-col>
      </v-row>
    </div>
    <Footer />
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
  background-image: url('../assets/zee-header-banner-2.jpg');
  background-repeat: no-repeat;
  background-position: center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
.network_nest {
  background-image: url('../assets/network-nest.png');
  background-repeat: no-repeat;
  background-position: center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: auto;

  padding: 5rem 20rem;
}
.our_team {
  padding: 2.5rem 20rem;

  background-image: url('../assets/bg-contt.jpg');
  background-repeat: no-repeat;
  background-position: center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
.our_team img {
  filter: grayscale(100%);
}
@media screen and (max-width: 600px) {
  .network_nest {
    padding: 5rem 2rem;
  }
  .our_team {
    padding: 2.5rem 2rem;
  }
  .v-avatar {
    width: 100px!important;
    height: 100px!important;
  }
}
@media screen and (min-width: 601px) and (max-width: 920px) {
  .network_nest {
    padding: 5rem;
  }
  .our_team {
    padding: 2.5rem 2rem;
  }
}
@media screen and (min-width: 921px) and (max-width: 1264px) {
  .network_nest {
    padding: 5rem;
  }
  .our_team {
    padding: 2.5rem 2rem;
  }
}
@media screen and (min-width: 1265px) and (max-width: 1904px) {
  
}
</style>