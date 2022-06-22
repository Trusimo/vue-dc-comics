<template>
    <div class="container">
        <img :src="thumb">
        <p>{{ series }}</p>
    </div>
</template>

<script>
export default {
    props: {
        thumb: String,
        series: String,
    },

    name: "ComicsCard",
    data() {
    return {
        
        }
    }
    
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>