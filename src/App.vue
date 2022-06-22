<template>
  <div id="app">
    <TheNavbar></TheNavbar>
    <ComicsContainer></ComicsContainer>
    <TheFooter></TheFooter>
    <TheBanner></TheBanner>
  </div>
</template>

<script>
import TheNavbar from "./components/TheNavbar.vue";
import TheFooter from "./components/TheFooter.vue";
import TheBanner from "./components/TheBanner.vue";
import ComicsContainer from "./components/ComicsContainer.vue";

export default {
  name: 'App',
  components: {
    TheNavbar,
    ComicsContainer,
    TheFooter,
    TheBanner,
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
