<template>
  <div id="app">
    <TheNavbar></TheNavbar>
  </div>
</template>

<script>
import TheNavbar from "./components/TheNavbar.vue";

export default {
  name: 'App',
  components: {
    TheNavbar
}
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
