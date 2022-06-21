<template>
  <div class="container">
    <div class="navbar" v-for="item in navitems">
    <img alt="DC Logo" :src="require('../assets/img/dc-logo.png')" />
      ciao
    </div>
  </div>
</template>

<script>
export default {
  name: "TheNavbar",
  data() {
    return {
      navitems: [
        "characters",
        "comics",
        "movies",
        "TV",
        "Games",
        "Collectibles",
        "Videos",
        "Fans",
        "News",
        "Shop"
      ]
    }
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .navbar {
    background-color: white;
    display: flex;
    justify-content: space-between;
  }
</style>
