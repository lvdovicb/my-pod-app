<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/profile">Profile</router-link>
    </div>
    <router-view />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";

export default {
  name: "app",
  components: {
    Header
  }
};
</script>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  font-weight: 500;
}
#nav {
  padding: 30px 30px 30px 70px;
  text-align: left;
  a {
    font-weight: bold;
    color: #2c3e50;
    font-size: 1.3rem;
    &.router-link-exact-active {
      color: #42b983;
      text-decoration: underline;
    }
  }
}
</style>
