<template>
    <v-btn color="#0067FF" @click="$router.push(link.link)" large text tile :class="['link']">
        <span class="text">{{link.text}}</span>
    </v-btn>
</template>

<script>
export default {
    props: ['link']
}
</script>

<style lang="scss">
.link{
    border-bottom: solid 3px black;
    &:hover, .current{
        border-bottom-color: white;
    }
    .text{
        font-family: "Roboto Condensed", Sans-serif;
    }
    }
</style>