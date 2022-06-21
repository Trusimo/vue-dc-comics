<template>
    <div class="container bg-dc">

        <img class="dc-big" alt="DC Logo" :src="require('../assets/img/dc-logo-bg.png')" />

        <div class="row flex">
            <div class="col-2">
                <h5>DC COMICS</h5>
                <ul v-for="(item, index) in dccomicslist" :key="index">
                    <li>{{item}}</li>
                </ul>
            </div>
            <div class="col-2">
                <h5>DC</h5>
                <ul v-for="(seconditem, index) in dc" :key="index">
                    <li>{{seconditem}}</li>
                </ul>
            </div>
            <div class="col-2">
                <h5>SITES</h5>
                <ul v-for="(thirditem, index) in sites" :key="index">
                    <li>{{thirditem}}</li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "TheFooter",
    data() {
        return {
            dccomicslist: [
                "Characters",
                "Comics",
                "Movies",
                "TV",
                "Games",
                "Videos",
                "News"
            ],

            dc: [
                "Terms of use",
                "Privacy Policy",
                "AD Choices",
                "Advertising",
                "Jobs",
                "Subscriptions",
                "Talent",
                "Workshops",
                "Certificate",
                "Ratings",
                "Show Help",
                "Contact us"
            ],

            sites: [
                "DC",
                "MAd Magazine",
                "DC Kids",
                "DC Universe",
                "DC PowerVisa"
            ]
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
        color: white;
    }

    .dc-big {
        height: 500px;
        position: absolute;
        right: 200px;
    }

    .flex {
        display: flex;
        gap: 70px;
    }

    ul {
        list-style: none;
        font-size: 12px;
    }

    h5 {
        font-size: 16px;
    }
</style>