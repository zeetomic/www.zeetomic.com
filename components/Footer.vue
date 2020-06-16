<template>
  <div class="footer">
    <div class="px-6 my-container">
      <v-row>
        <v-col>
          <p class="font-weight-medium title text-uppercase">Company</p>
          <v-btn light text to="/about"><span class="font-weight-thin text-capitalize">About Zeetomic</span></v-btn>
          <div>
            <v-btn light text to="/privacy"><span class="font-weight-thin text-capitalize">Privacy & Policy</span></v-btn>
          </div>
          <div>
            <v-btn light text to="/termofuse"><span class="font-weight-thin text-capitalize">Term of use</span></v-btn>
          </div>
        </v-col>
        <v-col class="d-flex justify-center">
          <div>
            <p class="font-weight-medium title text-uppercase">Solutions</p>
            <v-btn light text><span class="font-weight-thin text-capitalize">Customer Loyalty</span></v-btn>
            <div>
              <v-btn light text><span class="font-weight-thin text-capitalize">Crowdfunding And Vested</span></v-btn>
            </div>
            <div>
              <v-btn light text><span class="font-weight-thin text-capitalize">API for Payment Solutions</span></v-btn>
            </div>
          </div>
        </v-col>
        <v-col class="d-flex justify-center">
          <div>
            <p class="font-weight-medium title text-uppercase">Developers</p>
            <v-btn light text href="https://docs.zeetomic.com/" target="blank"><span class="font-weight-thin text-capitalize">Documentation</span></v-btn>
            <div>
              <v-btn light text href="https://github.com/zeetomic/" target="blank"><span class="font-weight-thin text-capitalize">GitHub</span></v-btn>
            </div>
          </div>
        </v-col>
        <v-col class="d-flex justify-end">
          <div>
            <p class="font-weight-medium title text-uppercase">Connect With Us</p>
            <v-btn class="ma-2" min-width="60px" outlined color="blue-grey darken-2" href="https://www.facebook.com/zeetomic" target="blank">
              <v-icon>fab fa-facebook</v-icon>
            </v-btn>
            <v-btn class="ma-2" min-width="60px" outlined color="blue-grey darken-2" href="https://t.me/zeetomic" target="blank">
              <v-icon>fab fa-telegram</v-icon>
            </v-btn>
            <br>
            <v-btn class="ma-2" min-width="60px" outlined color="blue-grey darken-2" href="https://www.linkedin.com/company/zeetomic" target="blank">
              <v-icon>fab fa-linkedin</v-icon>
            </v-btn>
            <v-btn class="ma-2" min-width="60px" outlined color="blue-grey darken-2" href="https://medium.com/zeetomic" target="blank">
              <v-icon>fab fa-linkedin</v-icon>
            </v-btn>
            <br>
          </div>
        </v-col>
      </v-row>
    </div>
    <div class="copyright py-2">
      <span class="white--text">Copyright © 2020 Zeetomic. All right reserved.
        A brainchild of SmallWorld Venture</span>
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
  color: black;
  background: #e8f1f5!important;
}
.copyright {
  background: #005691;
  text-align:center;
}
.my-container {
  padding: 0 10rem!important;
}
</style>