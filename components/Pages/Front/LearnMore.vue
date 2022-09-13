<template>
  <section>
        <v-row dense no-gutters>
            <v-col v-for="(section, i) in sections" :key="i" cols="4">

            </v-col>
        </v-row>
    </section>
</template>

<script>
export default {
    data(){return{
        sections: [
            {
                image: '',
                direction: ''
            },
            {
                image: '',
                direction: ''
            },
            {
                image: '',
                direction: ''
            },
            {
                image: '',
                direction: ''
            },
            {
                image: '',
                direction: ''
            },
            {
                image: '',
                direction: ''
            }
        ]
    }}
}
</script>

<style>

</style>