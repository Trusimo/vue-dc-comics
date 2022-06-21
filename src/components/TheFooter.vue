<template>
    <div class="container bg-dc">

        <img class="dc-big" alt="DC Logo" :src="require('../assets/img/dc-logo-bg.png')" />

    </div>
</template>

<script>
export default {
    name: "TheFooter",
    data() {
        return {
            
            
        }
    }
    
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .bg-dc {
        background-image:url(../assets/img/footer-bg.jpg);
        height: 400px;
        display: flex;
        position: relative;
    }

    .dc-big {
        height: 500px;
        position: absolute;
        right: 200px;
    }
</style>