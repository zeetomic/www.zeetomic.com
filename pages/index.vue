<template>
  <div>
    <div class="main">
      <Header />
      <div class="section1">
        <v-row>
          <v-col cols="12" xs="10" sm="11" md="10" lg="6" xl="6">
            <p class="font-weight-bold white--text semi-bold" style="line-height: 50px">The Platform for the Issuance and Management of Digital Asset</p>
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="12" xs="8" sm="8" md="10" lg="6" xl="6">
            <p class="white--text font-weight-regular">We provide trusted global solutions for creating a digital asset. Customer Loyalty | Real Estate | Vested Shares | Payment Solution</p>
          </v-col>
        </v-row>
      <v-btn large color="primary" href="https://github.com/zeetomic/mobile/releases/download/0.2.test/zee_test_v0_2.apk">
        <v-icon>mdi-android</v-icon> Get the android APK
      </v-btn>
      </div>
    </div>
    <div class="section2">
      <p class="font-weight-bold text-center semi-bold white--text">Recently Projects</p>
      <v-row class="pt-12">
        <v-col class="d-flex flex-column align-center justify-center">
          <div data-aos="fade-right" data-aos-duration="1500">
          <v-card max-width="320px" elevation="8">
            <img src="../assets/1.svg" alt="vitamin-air">
          </v-card>
          </div>
        </v-col>
        <v-col class="d-flex align-center">
          <div  style="text-align: start">
          <p class="font-weight-bold white--text" style="font-size: 30px">Blockchain as a Customer Loyalty solution</p>
          <p class="white--text">Customer loyalty programs allow companies to reward customers who make purchases frequently or on a specified period.</p>
          </div>
        </v-col>
      </v-row>
      <v-row>
        <v-col class="d-flex align-center">
          <div style="text-align: end">
            <p class="font-weight-bold white--text" style="font-size: 30px">Crowdfunding And Vested</p>
            <p class="white--text">Our Platform enables any startup to create an asset and accept crowdfunding secured by the Zeetomic custodian account.</p>
          </div>
        </v-col>
        <v-col class="d-flex flex-column align-center justify-center">
          <div data-aos="fade-left" data-aos-duration="1500">
          <v-card max-width="330px" elevation="8">
            <img src="../assets/2.svg" alt="vitamin-air">
          </v-card>
          </div>
        </v-col>
      </v-row>
      <v-row>
        <v-col class="d-flex flex-column align-center justify-center">
          <div data-aos="fade-right" data-aos-duration="1500">
          <v-card max-width="320px" elevation="8">
            <img src="../assets/3.svg" alt="vitamin-air">
          </v-card>
          </div>
        </v-col>
        <v-col class="d-flex align-center justify-start">
          <div style="text-align: start">
            <p class="font-weight-bold white--text" style="font-size: 30px">API for Payment Solutions</p>
            <p class="white--text">With our robust API developers can access payment ecosystems for a more dynamic transition of value.</p>
          </div>
        </v-col>
      </v-row>
    </div>
    <div class="section3">
      <v-carousel 
        cycle
        hide-delimiters 
        class="desktop_carousel"
      >
        <v-carousel-item>
          <v-card outlined height="100%">
            <v-row style="height: 100%">
              <v-col class="d-flex justify-center align-center">
                <img class="step1_img" src="../assets/step-1.png" alt="step-1">
              </v-col>
              <v-col  class="mx-auto" align-self="center">
                <div class="carousel_detail">
                  <div class="font-weight-bold text-center white--text semi-bold">How it work ?</div>
                  <div style="padding-top:2rem"></div>
                  <div class="text-center font-weight-regular regular white--text">Your customer identifies themselves vai require documents. </div>
                </div>
              </v-col>
            </v-row>
          </v-card>
        </v-carousel-item>
        <v-carousel-item>
          <v-card outlined height="100%">
            <v-row style="height: 100%">
              <v-col class="d-flex justify-center align-center">
                <img class="step1_img" src="../assets/step-1.png" alt="step-1">
              </v-col>
              <v-col class="mx-auto" align-self="center">
                <div class="carousel_detail">
                  <div class="font-weight-bold text-center semi-bold white--text">Integrate with existing POS</div>
                  <div style="padding-top:2rem"></div>
                  <div class="text-center font-weight-regular regular white--text">Your customer pays into items through your existing POS. </div>
                </div>
              </v-col>
            </v-row>
          </v-card>
        </v-carousel-item>
        <v-carousel-item>
          <v-card outlined height="100%">
            <v-row style="height: 100%">
              <v-col class="d-flex justify-center align-center">
                <img class="step1_img" src="../assets/step-1.png" alt="step-1">
              </v-col>
              <v-col class="mx-auto" align-self="center">
                <div class="carousel_detail">
                  <div class="font-weight-bold text-center semi-bold white--text">Reward Customer autonomously</div>
                  <div style="padding-top:2rem"></div>
                  <div class="text-center font-weight-regular regular white--text">Your customer received the reward automatically into their account.</div>
                </div>
              </v-col>
            </v-row>
          </v-card>
        </v-carousel-item>
        <v-carousel-item>
          <v-card outlined height="100%">
            <v-row style="height: 100%">
              <v-col class="d-flex justify-center align-center">
                <img class="step1_img" src="../assets/step-1.png" alt="step-1">
              </v-col>
              <v-col class="mx-auto" align-self="center">
                <div class="carousel_detail">
                  <div class="font-weight-bold text-center semi-bold white--text">Exchange</div>
                  <div style="padding-top:2rem"></div>               
                  <div class="text-center font-weight-regular regular white--text">From the trading account, token are exchangeable with trusted parties.</div>                
                </div>
              </v-col>
            </v-row>
          </v-card>
        </v-carousel-item>
      </v-carousel>
      <v-carousel 
        hide-delimiters
        cycle
        height="350"
        class="mobile_carousel"
      >
        <v-carousel-item>
          <v-card outlined height="100%">
            <v-row style="height: 100%">
              <v-col class="d-flex justify-center align-center">
                <img class="step1_img" src="../assets/step-1.png" alt="step-1">
              </v-col>
              <v-col class="mx-auto" align-self="center">
                <div class="carousel_detail">
                  <div class="font-weight-bold text-center semi-bold white--text">How it work ?</div>
                  <div style="padding-top:1rem"></div>
                  <div class="text-center font-weight-regular regular white--text">Your customer identifies themselves vai require documents. </div>
                </div>
              </v-col>
            </v-row>
          </v-card>
        </v-carousel-item>
        <v-carousel-item>
          <v-card outlined height="100%">
            <v-row style="height: 100%">
              <v-col class="d-flex justify-center align-center">
                <img class="step1_img" src="../assets/step-1.png" alt="step-1">
              </v-col>
              <v-col class="mx-auto" align-self="center">
                <div class="carousel_detail">
                  <div class="font-weight-bold text-center semi-bold white--text">Integrate with existing POS</div>
                  <div style="padding-top:1rem"></div>
                  <div class="text-center font-weight-regular regular white--text">Your customer pays into items through your existing POS. </div>
                </div>
              </v-col>
            </v-row>
          </v-card>
        </v-carousel-item>
        <v-carousel-item>
          <v-card outlined height="100%">
            <v-row style="height: 100%">
              <v-col class="d-flex justify-center align-center">
                <img class="step1_img" src="../assets/step-1.png" alt="step-1">
              </v-col>
              <v-col class="mx-auto" align-self="center">
                <div class="carousel_detail">
                  <div class="font-weight-bold text-center semi-bold white--text">Reward Customer autonomously</div>
                  <div style="padding-top:1rem"></div>
                  <div class="text-center font-weight-regular regular white--text">Your customer received the reward automatically into their account.</div>
                </div>
              </v-col>
            </v-row>
          </v-card>
        </v-carousel-item>
        <v-carousel-item>
          <v-card outlined height="100%">
            <v-row style="height: 100%">
              <v-col class="d-flex justify-center align-center">
                <img class="step1_img" src="../assets/step-1.png" alt="step-1">
              </v-col>
              <v-col class="mx-auto" align-self="center">
                <div class="carousel_detail">
                  <div class="font-weight-bold text-center semi-bold white--text">Exchange</div>
                  <div style="padding-top:1rem"></div>               
                  <div class="text-center font-weight-regular regular white--text">From the trading account, token are exchangeable with trusted parties.</div>                
                </div>
              </v-col>
            </v-row>
          </v-card>
        </v-carousel-item>
      </v-carousel>
    </div>
    <Mission />
  </div> 
</template>

<script>
import Footer from '~/components/Footer.vue';
import Header from '~/components/Header.vue';
import Mission from '~/components/Mission.vue';
export default {
  components: {
    Header,
    Footer,
    Mission
  }
}
</script>

<style scoped>
.main {
  background-image: url('../assets/zee-landing.jpg');
  background-repeat: no-repeat;
  background-position: center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: 100vh;
}
.zee-landing {
  width: 100%;
  position: absolute;
}
.section1 {
  padding: 10% 12%;
}
.section2 {
  padding: 2% 12%;
  /* background: #004a7c; */
  background-image: url('../assets/zee-header-banner.jpg');
  background-repeat: no-repeat;
  background-position: center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
.section2 img{
  max-width: 300px;
  min-height: 560px;
}
.section2 .v-card {
  background-image: url('../assets/bg-cont.jpg');
  background-repeat: no-repeat;
  background-position: center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  /* background: rgba(0, 0, 0, 0.1)!important; */
}
.section3 .v-card  {
  background-image: url('../assets/zee-header-netnest.png');
  background-repeat: no-repeat;
  background-position: center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  border: 0px!important;
  border-radius: 0px!important;
}
.carousel {
  padding: 5rem 7rem;
}
.step1_img{
  width: 400px;
}
.section4 {
  padding: 5% 17%;
}
.carousel_detail {
  padding: 0 4rem;
}
@media screen and (max-width: 600px) {
  .main {
    height: auto;
  }
  .network_nest {
    padding: 5rem 2rem;
  }
  .carousel {
    padding: 0rem 3rem;
  }
  .step1_img{
    width: 150px!important;
  }
  .desktop_carousel {
    display: none;
  }
}
@media screen and (min-width: 601px) and (max-width: 920px) {
  .main {
    height: auto;
  }
  .network_nest {
    padding: 5rem;
  }
  .mobile_carousel {
    display: none;
  }
}
@media screen and (min-width: 921px) and (max-width: 1264px) {
  .network_nest {
    padding: 5rem;
  }
   .mobile_carousel {
    display: none;
  }
}
@media screen and (min-width: 1265px) and (max-width: 1904px) {
  .mobile_carousel {
    display: none;
  }
}
@media screen and (min-width: 1920px) {
  .mobile_carousel {
    display: none;
  }
}
</style>