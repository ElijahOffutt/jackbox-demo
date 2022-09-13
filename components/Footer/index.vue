<template>
    <v-footer class="main-footer" app padless absolute>
        <v-container>
            <v-row>
                <v-col cols="5">

                </v-col>
                <v-col cols="4">
                    <v-row>
                        <v-col class="shrink">
                            <h3>Company</h3>
                            <ul>
                                <li v-for="(link, i) in companyLink" :key="i"></li>
                            </ul>
                        </v-col>
                        <v-col class="grow">

                        </v-col>
                    </v-row>
                </v-col>
                <v-col cols="3">

                </v-col>
                <v-col cols="12">
                    <v-row justify="space-between">
                        <v-col class="shrink">
                            &copy; 2022 Jackbox Games
                        </v-col>
                        <v-col>
                            <p>
                                <a href="">Terms of Service</a> | <a href="">Privacy Policy</a>
                            </p>
                        </v-col>
                    </v-row>
                </v-col>
            </v-row>
        </v-container>
    </v-footer>
</template>

<script>
import companyLinks from './Company.json'
import resourceLinks from './Resources.json'
export default {
    data(){return{
        companyLinks,
        resourceLinks
    }}
}
</script>

<style lang="scss">
.main-footer{
    background-color: black;
}
</style>