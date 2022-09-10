<template>
  <v-app dark>
    <v-main>
      <v-container fluid class="pa-0 ma-0">
        <Nav />
        <Nuxt />
      </v-container>
    </v-main>
    <v-footer app>
      <v-container>
        <v-row>
          <v-col cols="4"></v-col>
          <v-col cols="4"></v-col>
          <v-col cols="4"></v-col>
          <v-col cols="12">
            <v-row justify="space-between">
              <v-col class="shrink no-break"></v-col>
              <v-col class="shrink no-break"></v-col>
            </v-row>
          </v-col>
        </v-row>
      </v-container>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js'
    }
  }
}
</script>
