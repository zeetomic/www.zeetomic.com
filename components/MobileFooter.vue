<template>
  <div class="footer-mobile">
    <div class="d-flex justify-center align-center" style="padding: 2rem 0">
      <img class="zee_footer" src="~/assets/zeetomic-logo-footer.png" alt="zee_footer">
    </div>
    <p class="text-center grey--text">Copyright © 2018 Zeetomic. All right reserved.
      A brainchild of SmallWorld Venture</p>
    <div style="padding-top: 1rem"></div>
    <v-row>
      <v-col class="d-flex align-center justify-center">
        <v-btn class="ma-2" outlined small fab color="blue-grey darken-2" href="https://www.facebook.com/zeetomic" target="blank">
          <v-icon>fab fa-facebook</v-icon>
        </v-btn>
        <v-btn class="ma-2" outlined small fab color="blue-grey darken-2" href="https://t.me/zeetomic" target="blank">
          <v-icon>fab fa-telegram</v-icon>
        </v-btn>
        <v-btn class="ma-2" outlined small fab color="blue-grey darken-2" href="https://www.linkedin.com/company/zeetomic" target="blank">
          <v-icon>fab fa-linkedin</v-icon>
        </v-btn>
        <v-btn class="ma-2" outlined small fab color="blue-grey darken-2" href="https://medium.com/zeetomic" target="blank">
          <v-icon>fab fa-medium</v-icon>
        </v-btn>
      </v-col>
    </v-row>
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
.footer-mobile {
  background: #e8f1f5!important;
}
.zee_footer {
  width: 180px;
}
</style>