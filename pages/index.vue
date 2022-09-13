<template>
<div class="wrap">
  <Splash />
  <Hero />
  <Subscribe />
</div>
</template>

<script>
import Splash from './../components/Pages/Front/Splash.vue'
import Hero from './../components/Pages/Front/Hero.vue'
import Subscribe from './../components/Pages/Front/Subscribe.vue'
export default {
  components: {Splash, Hero, Subscribe},
  name: 'IndexPage'
}
</script>
