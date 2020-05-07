<template>
  <div class="footer">
    <div class="desktop">
      <div class="pa-6">
        <v-row>
          <img class="zee_footer pa-4" src="../assets/zeetomic-logo-footer.png" alt="zee_footer">
        </v-row>
        <v-row>
          <v-col>
            <p class="font-weight-bold title">Contact US</p>
            <p class="font-weight-bold">info@zeetomic.com</p>
          </v-col>
          <v-col>
            <p class="font-weight-bold title">Information</p>
            <v-btn text to="/about"><span class="font-weight-bold">About Zeetomic</span></v-btn>
            <div>
              <v-btn text to="/privacy"><span class="font-weight-bold">Privacy & Policy</span></v-btn>
            </div>
            <div>
              <v-btn text to="/termofuse"><span class="font-weight-bold">Term of use</span></v-btn>
            </div>
          </v-col>
        </v-row>
      </div>
      <v-row class="copyright">
        <v-row>
          <v-col class="d-flex align-end">
            <p class="px-6">Copyright © 2018 Zeetomic. All right reserved.
            A brainchild of SmallWorld Venture</p>
          </v-col>
          <v-col class=" d-flex align-center justify-end px-6">
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
      </v-row>
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
.footer {
  background: #ece7e7!important;
}
.zee_footer {
  width: 180px;
}
.copyright {
  background: #cfcaca;
}

@media only screen and (max-width: 500px) {
  .desktop {
    display: none;
  }
}
/* Tablet */
@media only screen and (min-width: 501px) and (max-width: 768px) {
  .mobile {
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