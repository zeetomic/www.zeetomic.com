<template>
<div>
  <div class="bar" v-if="showNav">
    <ul>
      <li v-for="(item, i) in items" :key="i">
        <v-btn text color="transperant" :to="item.to">
          {{item.title}}
        </v-btn>
        <v-divider></v-divider>
      </li>
      <li>
        <v-btn text color="transperant" href="" target="blank">Login</v-btn>
        <v-divider></v-divider>
      </li>
      <li>
        <v-btn outlined href="" target="blank">Sign Up</v-btn>
      </li>
    </ul>
  </div>

  <v-row class="pa-3 sidebar">
    <v-btn icon @click="showNav = !showNav">
      <v-icon>fas fa-bars</v-icon>
    </v-btn>
    <v-row justify="center" align="center">
      <img class="zee-header" src="../assets/zeetomic-logo-header.png" alt="Zeetomic">
    </v-row>
  </v-row>
</div>
</template>

<script>
export default {
  data() {
    return {
      showNav: false,

      items: [
        { title: 'Home', to: '/' },
        { title: 'About', to: '/about' },
        { title: 'privacy & policy', to: '/privacy' },
        { title: 'term of use', to: '/termofuse' },
        { title: 'blog', to: '/blog' },
      ]
    }
  }
}
</script>

<style scoped>
.zee-header {
  height: 30px;
  width: 170px;
}
ul li {
  list-style: none;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
ul {
  padding: 10px 6px!important;
}
.bar {
  overflow: hidden;
  position: absolute;
  background: #041c34;
  top: 60px;
  z-index: 2;
  /* transition: all 0.2s ease-in-out; */
}
</style>