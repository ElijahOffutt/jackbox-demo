<template>
  <section class="subscribe">
    <v-row justify="center">
        <v-col class="shrink">
            <v-card class="px-12 pt-5 pb-9" light>
                <v-card-title>
                    <h3 class="subscribe-title">SUBSCRIBE</h3>
                </v-card-title>
                <v-row dense>
                    <v-col cols="12" class="pb-7">
                        <span style="width: 300px; display: inline-block;">Be the first to hear the latest news about <br />The Jackbox Party Pack 9!</span>
                    </v-col>
                    <v-col cols="12">
                        <v-text-field hide-details outlined dense placeholder="Enter Your Email" />
                    </v-col>
                    <v-col cols="12">
                        <v-btn x-large block color="rgb(242, 99, 8)" class="white--text">yes, please!</v-btn>
                    </v-col>
                </v-row>
            </v-card>
        </v-col>
    </v-row>
  </section>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.subscribe{
    background-image: url('https://jackboxgames.b-cdn.net/wp-content/uploads/2019/10/email.jpg');
    background-position: center center;
    background-size: cover;
    padding: 65px 0;
    .subscribe-title{
        text-align: center;
    }
}
</style>