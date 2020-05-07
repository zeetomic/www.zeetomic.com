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
      <v-btn outlined large color="white" href="https://github.com/zeetomic/mobile/releases/download/0.2.test/zee_test_v0_2.apk">
        <v-icon>mdi-android</v-icon> Get the android APK
      </v-btn>
      </div>
    </div>
    <div class="section2">
      <p class="font-weight-bold text-center semi-bold">Recently Projects</p>
      <v-row>
        <v-col cols="12" xs="12" sm="12" md="4" lg="4" xl="4">
          <div data-aos="fade-right" data-aos-duration="1000">
          <v-card class="d-flex justify-center" elevation="6">
            <img src="../assets/1.svg" alt="vitamin-air">
          </v-card>
          <div style="padding-top:2rem"></div>
          <p class="font-weight-bold text-center" style="font-size: 20px">Blockchain as a Customer Loyalty solution</p>
          <p class="text-center">Customer loyalty programs allow companies to reward customers who make purchases frequently or on a specified period.</p>
          </div>
        </v-col>
        <v-col cols="12" xs="12" sm="12" md="4" lg="4" xl="4">
          <div data-aos="zoom-out" data-aos-duration="1000">
          <v-card class="d-flex justify-center" elevation="6">
            <img src="../assets/2.svg" alt="vitamin-air">
          </v-card>
          <div style="padding-top:2rem"></div>
          <p class="font-weight-bold text-center" style="font-size: 20px">Crowdfunding And Vested</p>
          <p class="text-center">Our Platform enables any startup to create an asset and accept crowdfunding secured by the Zeetomic custodian account.</p>
          </div>
        </v-col>
        <v-col cols="12" xs="12" sm="12" md="4" lg="4" xl="4">
          <div data-aos="fade-left" data-aos-duration="1000">
          <v-card class="d-flex justify-center" elevation="6">
            <img src="../assets/3.svg" alt="vitamin-air">
          </v-card>
          <div style="padding-top:2rem"></div>
          <p class="font-weight-bold text-center" style="font-size: 20px">API for Payment Solutions</p>
          <p class="text-center">With our robust API developers can access payment ecosystems for a more dynamic transition of value.</p>
          </div>
        </v-col>
      </v-row>
    </div>
    <div class="section3">
      <v-carousel 
        hide-delimiters 
        cycle
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
                  <div class="font-weight-bold text-center semi-bold" style="color:#485865">How it work ?</div>
                  <div style="padding-top:2rem"></div>
                  <div class="text-center font-weight-regular regular" style="color:#444444">Your customer identifies themselves vai require documents. </div>
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
                  <div class="font-weight-bold text-center semi-bold" style="color:#485865">Integrate with existing POS</div>
                  <div style="padding-top:2rem"></div>
                  <div class="text-center font-weight-regular regular" style="color:#444444">Your customer pays into items through your existing POS. </div>
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
                  <div class="font-weight-bold text-center semi-bold" style="color:#485865">Reward Customer autonomously</div>
                  <div style="padding-top:2rem"></div>
                  <div class="text-center font-weight-regular regular" style="color:#444444">Your customer received the reward automatically into their account.</div>
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
                  <div class="font-weight-bold text-center semi-bold" style="color:#485865">Exchange</div>
                  <div style="padding-top:2rem"></div>               
                  <div class="text-center font-weight-regular regular" style="color:#444444">From the trading account, token are exchangeable with trusted parties.</div>                
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
                  <div class="font-weight-bold text-center semi-bold" style="color:#485865">How it work ?</div>
                  <div style="padding-top:1rem"></div>
                  <div class="text-center font-weight-regular regular" style="color:#444444">Your customer identifies themselves vai require documents. </div>
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
                  <div class="font-weight-bold text-center semi-bold" style="color:#485865">Integrate with existing POS</div>
                  <div style="padding-top:1rem"></div>
                  <div class="text-center font-weight-regular regular" style="color:#444444">Your customer pays into items through your existing POS. </div>
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
                  <div class="font-weight-bold text-center semi-bold" style="color:#485865">Reward Customer autonomously</div>
                  <div style="padding-top:1rem"></div>
                  <div class="text-center font-weight-regular regular" style="color:#444444">Your customer received the reward automatically into their account.</div>
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
                  <div class="font-weight-bold text-center semi-bold" style="color:#485865">Exchange</div>
                  <div style="padding-top:1rem"></div>               
                  <div class="text-center font-weight-regular regular" style="color:#444444">From the trading account, token are exchangeable with trusted parties.</div>                
                </div>
              </v-col>
            </v-row>
          </v-card>
        </v-carousel-item>
      </v-carousel>
    </div>
    <div class="network_nest">
      <v-row data-aos="fade-right" data-aos-duration="3000">
        <v-col cols="12" xs="12" sm="12" md="6" lg="6" xl="6" style="text-align: end">
          <p class="font-weight-bold semi-bold" style="color:#485865">Mission</p>
          <p class="font-weight-regular regular" style="color:#444444">Fast, simple and cost reduction for security/utility token issuing platform.</p>
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
    <!-- <div class="section4">
      <p class="font-weight-bold text-center semi-bold">Recently Updates</p>
      <v-row>
        <v-col cols="12" xs="12" sm="12" md="4" lg="4" xl="4">
          <v-card class="d-flex justify-center" elevation="6">
            <img src="../assets/city.jpg" alt="vitamin-air">
          </v-card>
          <div style="padding-top:2rem"></div>
          <p class="font-weight-bold text-center" style="font-size: 20px">Community Incentivise Platform Base on Smart Contract</p>
          <p class="text-center">Zeeva ultivmate goal is to makes the network more decentralized, efficient, equalized, robust and secure, thus enabling healthier,safer, and more open internet for community.</p>
        </v-col>
        <v-col cols="12" xs="12" sm="12" md="4" lg="4" xl="4">
          <v-card class="d-flex justify-center" elevation="6">
            <img src="../assets/city-1.jpg" alt="vitamin-air">
          </v-card>
          <div style="padding-top:2rem"></div>
          <p class="font-weight-bold text-center" style="font-size: 20px">Decentralized Internet Sharing</p>
          <p class="text-center">Zeeva ultivmate goal is to makes the network more decentralized, efficient, equalized, robust and secure, thus enabling healthier,safer, and more open internet for community.</p>
        </v-col>
        <v-col cols="12" xs="12" sm="12" md="4" lg="4" xl="4">
          <v-card class="d-flex justify-center" elevation="6">
            <img src="../assets/city-2.jpg" alt="vitamin-air">
          </v-card>
          <div style="padding-top:2rem"></div>
          <p class="font-weight-bold text-center" style="font-size: 20px">ISO Listing and Trading</p>
          <p class="text-center">Zeeva ultivmate goal is to makes the network more decentralized, efficient, equalized, robust and secure, thus enabling healthier,safer, and more open internet for community.</p>
        </v-col>
      </v-row>
    </div> -->
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
  background-image: url('../assets/zee-landing.jpg');
  background-repeat: no-repeat;
  background-position: center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
.zee-landing {
  width: 100%;
  position: absolute;
}
.section1 {
  padding: 10% 17%;
}
.section2 {
  padding: 5% 17%;
}
.section2 img{
  width: 300px
}
.section2 .v-card {
  background-image: url('../assets/bg-cont.jpg');
  background-repeat: no-repeat;
  background-position: center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
.section3 .v-card {
  background-image: url('../assets/bg-cont.jpg');
  background-repeat: no-repeat;
  background-position: center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
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
@media screen and (max-width: 600px) {
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