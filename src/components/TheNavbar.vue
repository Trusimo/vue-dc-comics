<template>
  <div class="container">
    <img alt="DC Logo" :src="require('..assets/dc-logo.png')" />
    <div class="navbar">
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

      ]
    }
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .navbar {
    display: flex;
  }
</style>
