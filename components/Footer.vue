<template>
  <div class="footer">
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
          <v-icon>mdi-medium</v-icon>
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
.footer {
  background: #ece7e7!important;
  padding: 2rem 35rem;
}
.zee_footer {
  width: 200px;
}
@media screen and (max-width: 600px) {
  .footer {
    padding: 2rem;
  }
}
@media screen and (min-width: 601px) and (max-width: 920px) {
  .footer {
    padding: 2rem 10rem;
  }
}
@media screen and (min-width: 921px) and (max-width: 1264px) {
  .footer {
    padding: 2rem 5rem;
  }
}
@media screen and (min-width: 1265px) and (max-width: 1904px) {
  .footer {
    padding: 2rem 25rem;
  }
}

</style>