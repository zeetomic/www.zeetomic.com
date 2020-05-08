<template>
  <div>
    <div class="main">
      <Header />
      <div style="padding: 5rem 18%">
        <p class="white--text font-weight-bold text-center" style="font-size: 48px">BLOG</p>
      </div>
    </div>
    <div class="blog">
      <p class="text-center grey--text font-weight-regular semi-bold">Coming Soon...</p>
      <v-row>
        <v-col cols="12" xs="12" sm="12" md="4" lg="4" xl="4">
          <v-sheet
            :color="`grey ${theme.isDark ? 'darken-2' : 'lighten-4'}`"
            class="px-3 pt-3 pb-3"
          >
            <v-skeleton-loader
              class="mx-auto"
              max-width="300"
              type="card"
            ></v-skeleton-loader>
          </v-sheet>
        </v-col>
        <v-col cols="12" xs="12" sm="12" md="4" lg="4" xl="4">
          <v-sheet
            :color="`grey ${theme.isDark ? 'darken-2' : 'lighten-4'}`"
            class="px-3 pt-3 pb-3"
          >
            <v-skeleton-loader
              class="mx-auto"
              max-width="300"
              type="card"
            ></v-skeleton-loader>
          </v-sheet>
        </v-col>
        <v-col cols="12" xs="12" sm="12" md="4" lg="4" xl="4">
          <v-sheet
            :color="`grey ${theme.isDark ? 'darken-2' : 'lighten-4'}`"
            class="px-3 pt-3 pb-3"
          >
            <v-skeleton-loader
              class="mx-auto"
              max-width="300"
              type="card"
            ></v-skeleton-loader>
          </v-sheet>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" xs="12" sm="12" md="4" lg="4" xl="4">
          <v-sheet
            :color="`grey ${theme.isDark ? 'darken-2' : 'lighten-4'}`"
            class="px-3 pt-3 pb-3"
          >
            <v-skeleton-loader
              class="mx-auto"
              max-width="300"
              type="card"
            ></v-skeleton-loader>
          </v-sheet>
        </v-col>
        <v-col cols="12" xs="12" sm="12" md="4" lg="4" xl="4">
          <v-sheet
            :color="`grey ${theme.isDark ? 'darken-2' : 'lighten-4'}`"
            class="px-3 pt-3 pb-3"
          >
            <v-skeleton-loader
              class="mx-auto"
              max-width="300"
              type="card"
            ></v-skeleton-loader>
          </v-sheet>
        </v-col>
        <v-col cols="12" xs="12" sm="12" md="4" lg="4" xl="4">
          <v-sheet
            :color="`grey ${theme.isDark ? 'darken-2' : 'lighten-4'}`"
            class="px-3 pt-3 pb-3"
          >
            <v-skeleton-loader
              class="mx-auto"
              max-width="300"
              type="card"
            ></v-skeleton-loader>
          </v-sheet>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>
import Footer from '~/components/Footer.vue';
import Header from '~/components/Header.vue';
export default {
  inject: ['theme'],
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
.blog {
  padding: 4rem;
}
</style>