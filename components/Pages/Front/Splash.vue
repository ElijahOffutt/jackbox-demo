<template>
    <section class="splash">
        <div class="floats"></div>
        <v-container class="content pa-12">
            <v-row>
                <v-col class="shrink">
                    <v-row justify="center" align="center">
                        <v-col>
                            <v-img height="200px" width="150px" src="https://jackboxgames.b-cdn.net/wp-content/uploads/2021/09/JPP8_Logo_Portrait-e1631053882628.png" />
                        </v-col>
                    </v-row>
                </v-col>
                <v-col class="text grow">
                    <h2>The JackBox Party Pack 8</h2> <br />
                    <p>The eighth installment of the beloved Jackbox Party Pack franchise is here! Five hilarious new games will energize your next game night, holiday party, happy hour, or video call. <br /><br />

No extra controllers needed – players use their phones or tablets to play along! Got a bigger group? Play with up to 10 players and up to 10,000 audience members.<br /></p>
                    <p><b>The Jackbox Party Pack 8 is currently in English only. This game does not support online matchmaking but can still be enjoyed remotely using livestreaming services or video conferencing tools.</b></p>
                </v-col>
                <v-col class="shrink">
                    <v-card width="200px" class="right-card pt-5 pb-3" ripple>
                        <p style="text-align: center;">
                            buy steam code <br />
                            now <br />
                            (U.S. Only)
                        </p>
                    </v-card>
                    <p class="price pt-7"><b>$29.99</b></p>
                    <p class="platforms"><i>PC / MAC / LINUX</i></p>
                </v-col>
            </v-row>
        </v-container>
    </section>
</template>


<style lang="scss" scoped>
.splash{
    background-image: url(https://jackboxgames.b-cdn.net/wp-content/uploads/2021/09/PP8_DamaskTileLayered-copy-scaled.jpg);
    background-position: top center;
    background-size: contain;
    background-color: #F1F1F1;
    height: 900px;
    position: relative;
    .content{
        position: absolute;
        background-color: white;
        color: black;
        bottom: 0;
        left: 50%;
        transform: translateX(-50%); 
        .text{
            font-size: 1.25em;
        }
        .right-card{
            background-color: #F26308;
            font-weight: 100;
            font-family: impact;
            text-transform: uppercase;
            font-size: 1.5em;
        }
        .price { 
            color: red; 
            text-align: center;
            font-size: 1.5em;
        }
        .platforms{
            text-align: center;
            font-weight: 600;
        }
    }
}
</style>