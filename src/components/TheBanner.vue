<template>
    <div class="container flex">
        <button>SIGN UP NOW</button>

        <div class="socials">
            <h5>FOLLOW US</h5>
            <img class="social-icons" :src="require('../assets/img/footer-facebook.png')" />
            <img class="social-icons" :src="require('../assets/img/footer-twitter.png')" />
            <img class="social-icons" :src="require('../assets/img/footer-youtube.png')" />
            <img class="social-icons" :src="require('../assets/img/footer-pinterest.png')" />
            <img class="social-icons" :src="require('../assets/img/footer-periscope.png')" />
        </div>
    </div>
</template>

<script>
export default {
    name: "TheBanner",
    data() {
        return {

        }
    }
    
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.flex {
    display: flex;
    justify-content: space-between;
    background-color: #303030;
    padding: 30px;
    position: fixed;
    right: 99px;
    width: 100%
}

button {
    padding: 10px;
    border: 4px solid blue;
    background-color: #303030;
    color: white;


    &:hover {
        background-color: grey;
    }
}

.socials {
    display: flex;
    justify-content: space-around;
    align-items: center;
    gap: 20px;
}

.social-icons {
    width: 40px;
    height: 40px;
}

h5 {
    color: #1a68e8;
}
</style>