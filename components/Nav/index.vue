<template>
    <v-row style="height: 175px !important; background-color: black;" dense no-gutters align="start">
        <v-col cols="12" class="banner">
            <h2>Click HERE to pre-order The Jackbox Party Pack 9 Steam codes and receive 10% off your purchase!</h2>
        </v-col>
        <v-col cols="12" class="links">
            <v-row no-gutters dense class="ma-0 pa-0" justify="space-between" align="center">
                <v-col class="shrink ml-5">
                    <v-img @click="$router.push('/')" height="50px" width="170px" src="https://jackboxgames.b-cdn.net/wp-content/uploads/2020/05/Jackbox-Games-Logo-Web.png" />
                </v-col>
                <v-col class="shrink mr-5 no-break">
                    <Link v-for="(link, i) in links" :key="i" :link="link" />
                </v-col>
            </v-row>
        </v-col>
    </v-row>
</template>

<script lang="ts">
import Vue from 'vue'
import Link from './Link.vue'
let links = require('./links.json')
export default Vue.extend({
    components: {Link},
    data(){return{
        links
    }}
})
</script>

<style scoped lang="scss">
.v-toolbar__content{
    margin: 0 !important;
    padding: 0 !important;
}
.banner{
    background-color: #F26308;
    color: #FEF053;
    height: 65px;
    h2{ text-align: center; margin: 0; line-height: 80px; font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif; font-weight: 100; letter-spacing: 1.25px; }
}
.links{
    background-color: black;
    height: 50px !important;
}
.no-break{
    white-space: nowrap;
}
</style>