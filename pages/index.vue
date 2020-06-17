<template>
  <div>
    <div class="image">
      <div class="section1">
        <v-row>
          <v-col cols="12" xs="10" sm="11" md="10" lg="6" xl="6">
            <p class="display-2" style="line-height: 50px">The Platform for the Issuance and Management of Digital Asset</p>
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="12" xs="8" sm="8" md="10" lg="6" xl="6">
            <p class="">We provide trusted global solutions for creating a digital asset.<br>
              Customer Loyalty | Real Estate | Vested Shares | Payment Solution
            </p>
          </v-col>
        </v-row>
      </div>
    </div>
    <div class="section2">
      <p class="text-center display-2">Recently Project</p>
      <v-row class="pt-12">
        <v-col class="d-flex flex-column align-center justify-center">
          <div data-aos="fade-right" data-aos-duration="1500">
            <v-card light max-width="320px" elevation="8">
              <v-img :src="img" min-width="300px" min-height="560px"></v-img>
            </v-card>
          </div>
        </v-col>
        <v-col class="d-flex align-center">
          <div  style="text-align: start">
          <p class="font-weight-bold display-1">Blockchain as a Customer Loyalty solution</p>
          <p>Customer loyalty programs allow companies to reward customers who make purchases frequently or on a specified period.</p>
          </div>
        </v-col>
      </v-row>
      <v-row>
        <v-col class="d-flex align-center">
          <div style="text-align: end">
            <p class="font-weight-bold display-1">Crowdfunding And Vested</p>
            <p class="white--text">Our Platform enables any startup to create an asset and accept crowdfunding secured by the Zeetomic custodian account.</p>
          </div>
        </v-col>
        <v-col class="d-flex flex-column align-center justify-center">
          <div data-aos="fade-left" data-aos-duration="1500">
            <v-card light max-width="330px" elevation="8">
              <v-img :src="img2" min-width="300px" min-height="560px"></v-img>
            </v-card>
          </div>
        </v-col>
      </v-row>
      <v-row>
        <v-col class="d-flex flex-column align-center justify-center">
          <div data-aos="fade-right" data-aos-duration="1500">
          <v-card light max-width="320px" elevation="8">
            <v-img :src="img3" min-width="300px" min-height="560px"></v-img>
          </v-card>
          </div>
        </v-col>
        <v-col class="d-flex align-center justify-start">
          <div style="text-align: start">
            <p class="font-weight-bold display-1">API for Payment Solutions</p>
            <p>With our robust API developers can access payment ecosystems for a more dynamic transition of value.</p>
          </div>
        </v-col>
      </v-row>
    </div>
    <div class="section3">
      <v-carousel
        cycle
        height="600"
        hide-delimiter-background
        show-arrows-on-hover
      >
        <v-carousel-item
          v-for="(slide, i) in title"
          :key="i"
        >
          <v-sheet height="100%">
            <v-row
              class="fill-height"
              align="center"
              justify="center"
            >
              <v-col cols="12" md="6" lg="6" xl="6" class="d-flex justify-center">
                <v-img :src="step1"  max-width="400px"></v-img>
              </v-col>
              <v-col cols="12" md="6" lg="6" xl="6" class="text-center">
                <p class="display-1">{{ slide }}</p>
                <p class="title">{{ info[i] }}</p>
              </v-col>
            </v-row>
          </v-sheet>
        </v-carousel-item>
      </v-carousel>
    </div>
    <Mission />
  </div>
</template>

<script>
import Mission from '~/components/Mission.vue';

export default {
  layout: ({ isMobile }) => isMobile ? 'mobile' : 'default',
  head: {
    title: 'Zeetomic',
    meta: [
      { hid: 'description', name: 'description', content: 'The Platform for the Issuance and Management of Digital Asset' }
    ],
  },
  components: {
    Mission
  },
  data() {
    return {
      zee_landing: require('~/assets/zee-landing.jpg'),

      img: require('~/assets/1.svg'),
      img2: require('~/assets/2.svg'),
      img3: require('~/assets/3.svg'),
      step1: require('~/assets/step-1.png'),

      title: [
        'How it work ?',
        'Integrate with existing POS',
        'Reward Customer autonomously',
        'Exchange'
      ],
      info: [
        'Your customer identifies themselves via require documents.',
        'Your customer pays into items through your existing POS.',
        'Your customer received the reward automatically into their account.',
        'From the trading account, token are exchangeable with trusted parties.'
      ]
    }
  }
}
</script>

<style scoped>
.image {
  background-image: url('../assets/zee-landing.jpg');
  background-repeat: no-repeat;
  background-position: center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: 100vh;
}
.section1 {
  padding: 16% 12%;
}
.section2 {
  padding: 2% 12%;
  background-image: url('../assets/zee-header-banner.jpg');
  background-repeat: no-repeat;
  background-position: center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
.section3 .v-sheet  {
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

@media screen and (max-width: 600px) {
  .network_nest {
    padding: 5rem 2rem;
  }
}
</style>