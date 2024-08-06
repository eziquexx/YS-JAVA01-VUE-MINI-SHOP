<template>
  <div>
    <HeaderArea />
    <router-view />
    <FooterArea />
  </div>
</template>


<script>
import HeaderArea from './layouts/HeaderArea.vue';
import FooterArea from './layouts/FooterArea.vue';

export default {
  components: {
    HeaderArea,
    FooterArea,
  },
  setup() {

  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
