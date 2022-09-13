<template>
  <section>
    <v-container>
        <v-row>
            <v-col cols="12">
                <h2 class="lp-header">latest posts</h2>
            </v-col>
            <v-col cols="12">
                <v-slide-group>
                    <v-slide-item v-for="(slide, i) in slides" :key="i">
                        <v-card>
                            <v-card-image>

                            </v-card-image>
                            <v-card-title>

                            </v-card-title>
                            <v-subheader></v-subheader>
                            <v-card-text></v-card-text>
                        </v-card>
                    </v-slide-item>
                </v-slide-group>
            </v-col>
        </v-row>
    </v-container>
  </section>
</template>

<script>
export default {
    data(){return{
        slides: [
            {

            }
        ]
    }}
}
</script>

<style>

</style>