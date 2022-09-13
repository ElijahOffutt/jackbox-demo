<template>
   <section class="hero sky">
    <div class="poster">
        <div class="content">
            <v-row justify="center">
                <v-col class="shrink">
                    <v-btn color="primary" x-large class="hero-button">
                        learn more
                    </v-btn>
                </v-col>
                <v-col class="shrink">
                    <v-btn color="primary" x-large class="hero-button">
                        pre-order for steam
                    </v-btn>
                </v-col>
            </v-row>
        </div>
    </div>
    <span class="plan-your-party">
        plan your party
    </span>
   </section>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
.sky{
    background-image: url('https://jackboxgames.b-cdn.net/wp-content/uploads/2022/08/JPP9Sky.jpg');
    background-position: top center;
    background-size: cover;
}
.hero{
    .poster{
        margin: 0 auto;
        background-image: url('https://jackboxgames.b-cdn.net/wp-content/uploads/2022/08/JPP9_Wide.png');
        background-position: bottom center;
        background-size: contain;
        height: 700px;
        .content{
            padding-top: 575px;
            .hero-button{
                width: 250px;
                &:hover{ transform: scale(1.1); }
            }
        }
    }
    .plan-your-party{
        background-color: black;
        text-align: center;
        display: inline-block;
        width: 100%;
        padding: 40px 0;
        text-transform: uppercase;
        font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
        font-size: 4em;
        position: relative;
        &:after{
            content: "";
            display: block;
            position: absolute;
            background-color: black;
            height: 40px;
            width: 40px;
            float: left;
            top: 0;
            left: 50%;
            transform: translate(-50%, -50%) rotate(45deg);
        }
    }
}
</style>