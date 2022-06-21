<template>
  <div class="container">
    <div class="navbar">

      <img alt="DC Logo" :src="require('../assets/img/dc-logo.png')" />

    
        <ul class="flex" v-for="(navitem, index) in navitems" :key="index">
          <li>{{navitem}}</li>
        </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "TheNavbar",
  data() {
    return {
      navitems: [
        "Characters",
        "Comics",
        "Movies",
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
  ul {
    list-style: none;
  }
  
  .navbar {
    background-color: white;
    display: flex;
    justify-content: space-between;
  }

  .flex {
    display: flex;
    gap: 10px;
  }
</style>
