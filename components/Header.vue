<template>
<div>
  <v-app-bar
    flat
    color="transparent"
    class="header"
  >
    <v-btn color="transparent" text nuxt to="/">
      <img class="zee-header" src="../assets/zeetomic-logo-header.png" alt="zee_header">
    </v-btn>
    <v-spacer></v-spacer>
    <v-btn text large class="white--text font-weight-bold" nuxt to="/about">About</v-btn>
    <v-btn text large class="white--text font-weight-bold" nuxt to="/blog">Blog</v-btn>
    <v-spacer></v-spacer>
    <v-btn text large class="white--text font-weight-bold" href="https://web-wallet.now.sh/login">Log In</v-btn>
    <v-btn outlined class="white--text font-weight-bold" href="https://web-wallet.now.sh/signup">Sign Up</v-btn>
  </v-app-bar>
  <!-- Mobile -->
  <div class="sidebar_bg" @click="CloseBurger()" :class="{'showBG':showNavbar}"></div>
  <div class="sidebar" :class="{'show':showNavbar}">
    <transition name="el-fade-in">
      <ul v-show="showlink" class="text-center">
        <li>
          <v-btn text color="transparent" to="/">
            <img style="width: 80px" src="../assets/zeetomic-logo-header.png" alt="zee_header">
          </v-btn>
        </li>
        <v-divider dark></v-divider>
        <li>
          <v-btn text color="transperant" nuxt to="/about">
            <span class="white--text">About</span>
          </v-btn>
        </li>
        <v-divider dark></v-divider>
        <li>
          <v-btn text color="transperant" nuxt to="/privacy">
            <span class="white--text">Privacy & Policy</span>
          </v-btn>
        </li>
        <v-divider dark></v-divider>
        <li>
          <v-btn text color="transperant" nuxt to="/termofuse">
            <span class="white--text">Term Of Use</span>
          </v-btn>
        </li>
        <v-divider dark></v-divider>
        <li>
          <v-btn text color="transperant" nuxt to="/blog">
            <span class="white--text">Blog</span>
          </v-btn>
        </li>
        <v-divider dark></v-divider>
        <li>
          <v-btn text color="transperant" nuxt href="https://web-wallet.now.sh/login">
            <span class="white--text">Login</span>
          </v-btn>
        </li>
        <v-divider dark></v-divider>
        <li>
          <v-btn text outlined dark large class="white--text" nuxt href="https://web-wallet.now.sh/signup">
            <span>Sign Up</span>
          </v-btn>
        </li>
      </ul>
    </transition>
  </div>
  <div class="navbar">
    <v-row>
      <v-btn text>
        <v-icon color="white" style="font-size: 2rem" @click="openNavbar()">mdi-menu</v-icon>
      </v-btn>
      <v-row justify="center" align="center">
        <v-btn text nuxt to="/">
          <img class="zee-header" src="../assets/zeetomic-logo-header.png" alt="zee_header">
        </v-btn>
      </v-row>
    </v-row>
  </div>
</div>
</template>

<script>
export default {
  data() {
    return {
      showNavbar: false,
      showlink: false
    };
  },
  methods: {
    openNavbar() {
      if (this.showNavbar) {
        this.showlink = false;
        this.showNavbar = false;
      } else {
        this.showNavbar = true;
        this.showlink = true;
      }
    },
    CloseBurger() {
      this.showNavbar = false;
      this.showlink = false;
    },
  }
}
</script>

<style lang="less" scoped>
.zee-header {
  width: 170px;
}
.header {
  padding: 0 17%;
  padding-top: 1%; 
}
.navbar {
  padding: 1rem 3rem 0 2rem;
}
.sidebar {
  width: 0;
  height: 100vh;
  background: #063e63;
  position: fixed;
  z-index: 3;
  transition: all 0.2s ease-in-out;
  ul {
    padding: 0;
  }
  li {
    list-style: none;
    margin: 1rem 35%;
  }
}
.sidebar_bg {
  width: 0;
  height: 100%;
  z-index: 2;
  position: fixed;
  overflow: hidden;
  background: rgba(40, 43, 46, 0.4);
}
&.show {
  width: 60%;
}
&.showBG {
  width: 100%;
}
@media screen and (max-width: 600px) {
  .v-app-bar {
    display: none;
  }
}
@media screen and (min-width: 601px) and (max-width: 920px) {
  .v-app-bar {
    display: none;
  }
}
@media screen and (min-width: 921px) and (max-width: 1264px) {
  .navbar {
    display: none;
  }
}
@media screen and (min-width: 1265px) and (max-width: 1904px) {
  .navbar {
    display: none;
  }
}
@media screen and (min-width: 1920px) {
  .navbar {
    display: none;
  }
}
</style>