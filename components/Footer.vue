<template>
  <div class="footer">
    <div class="desktop">
      <div class="pa-6 my-container">
        <v-row>
          <!-- <img class="zee_footer pa-4" src="../assets/zeetomic-logo-footer.png" alt="zee_footer"> -->
        </v-row>
        <v-row>
          <v-col>
            <p class="font-weight-medium title text-uppercase">Company</p>
            <v-btn text to="/about"><span class="font-weight-thin text-capitalize">About Zeetomic</span></v-btn>
            <div>
              <v-btn text to="/privacy"><span class="font-weight-thin text-capitalize">Privacy & Policy</span></v-btn>
            </div>
            <div>
              <v-btn text to="/termofuse"><span class="font-weight-thin text-capitalize">Term of use</span></v-btn>
            </div>
          </v-col>
          <v-col class="d-flex justify-center">
            <div>
              <p class="font-weight-medium title text-uppercase">Solutions</p>
              <v-btn text><span class="font-weight-thin text-capitalize">Customer Loyalty</span></v-btn>
              <div>
                <v-btn text><span class="font-weight-thin text-capitalize">Crowdfunding And Vested</span></v-btn>
              </div>
              <div>
                <v-btn text><span class="font-weight-thin text-capitalize">API for Payment Solutions</span></v-btn>
              </div>
            </div>
          </v-col>
          <v-col class="d-flex justify-center">
            <div>
              <p class="font-weight-medium title text-uppercase">Developers</p>
              <v-btn text href="https://docs.zeetomic.com/" target="blank"><span class="font-weight-thin text-capitalize">Documentation</span></v-btn>
              <div>
                <v-btn text href="https://github.com/zeetomic/" target="blank"><span class="font-weight-thin text-capitalize">GitHub</span></v-btn>
              </div>
            </div>
          </v-col>
          <v-col class="d-flex justify-end">
            <div>
              <p class="font-weight-medium title text-uppercase">Connect With Us</p>
              <v-btn class="ma-2" min-width="60px" outlined color="blue-grey darken-2" href="https://www.facebook.com/zeetomic" target="blank">
                <v-icon>mdi-facebook</v-icon>
              </v-btn>
              <v-btn class="ma-2" min-width="60px" outlined color="blue-grey darken-2" href="https://t.me/zeetomic" target="blank">
                <v-icon>mdi-telegram</v-icon>
              </v-btn>
              <br>
              <v-btn class="ma-2" min-width="60px" outlined color="blue-grey darken-2" href="https://www.linkedin.com/company/zeetomic" target="blank">
                <v-icon>mdi-linkedin</v-icon>
              </v-btn>
              <v-btn class="ma-2" min-width="60px" outlined color="blue-grey darken-2" href="https://medium.com/zeetomic" target="blank">
                <img src="~/assets/medium.svg" style="width: 20px">
              </v-btn>
              <br>
            </div>
          </v-col>
        </v-row>
      </div>
      <div class="copyright py-2">
        <span class="white--text">Copyright © 2018 Zeetomic. All right reserved.
          A brainchild of SmallWorld Venture</span>
      </div>
    </div>


  <!-- Mobile -->
    <div class="mobile footer-mobile">
      <div class="d-flex justify-center align-center" style="padding: 2rem 0">
        <img class="zee_footer" src="../assets/zeetomic-logo-footer.png" alt="zee_footer">
      </div>
      <p class="text-center">Copyright © 2018 Zeetomic. All right reserved.
        A brainchild of SmallWorld Venture</p>
      <div style="padding-top: 1rem"></div>
      <v-row>
        <v-col class="d-flex align-center justify-center">
          <v-btn class="ma-2" outlined small fab color="blue-grey darken-2" href="https://www.facebook.com/zeetomic" target="blank">
            <v-icon>mdi-facebook</v-icon>
          </v-btn>
          <v-btn class="ma-2" outlined small fab color="blue-grey darken-2" href="https://t.me/zeetomic" target="blank">
            <v-icon>mdi-telegram</v-icon>
          </v-btn>
          <v-btn class="ma-2" outlined small fab color="blue-grey darken-2" href="https://www.linkedin.com/company/zeetomic" target="blank">
            <v-icon>mdi-linkedin</v-icon>
          </v-btn>
          <v-btn class="ma-2" outlined small fab color="blue-grey darken-2" href="https://medium.com/zeetomic" target="blank">
            <img src="~/assets/medium.svg" style="width: 20px">
          </v-btn>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.v-btn {
  padding: 1rem 0!important;
}
.footer {
  /* background: #ece7e7!important; */
  background: #e8f1f5!important;
  
  /* background-image: url('../assets/wave.svg');
  background-repeat: no-repeat;
  background-position: center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover; */
}
.zee_footer {
  width: 180px;
}
.copyright {
  /* background: #cfcaca; */
  background: #005691;
  text-align:center;
}
.my-container {
  padding: 0 10rem!important;
}
@media only screen and (max-width: 500px) {
  .desktop {
    display: none;
  }
}
/* Tablet */
@media only screen and (min-width: 501px) and (max-width: 768px) {
  .desktop {
    display: none
  } 
}
/* Normal */
@media only screen and (min-width: 769px) and (max-width: 1199px){
  .mobile {
    display: none
  } 
}
/* Large monitor */
@media only screen and (min-width: 1200px) and (max-width: 1919px) {
  .mobile {
    display: none
  }      
}
/* Landscape */
@media only screen and (max-height: 500px) {
  .mobile {
    display: none
  } 
}
/* Widescreen */
@media only screen and (min-width: 1920px) {
  .mobile {
    display: none
  } 
}
</style>