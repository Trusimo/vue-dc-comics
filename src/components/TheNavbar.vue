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
        "CHARACTERS",
        "COMICS",
        "MOVIES",
        "TV",
        "GAMES",
        "COLLECTIBLES",
        "VIDEOS",
        "FANS",
        "NEWS",
        "SHOP"
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
    margin: 30px;

  // da sistemare ma è per provare l'&:hover
    &:hover{
      color:rgb(14, 48, 184);
    }
  }

  .flex {
    display: flex;
    gap: 10px;
  }
</style>
