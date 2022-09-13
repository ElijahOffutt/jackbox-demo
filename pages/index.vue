<template>
<div class="wrap">
  <Splash />
  <Hero />
</div>
</template>

<script>
import Splash from './../components/Pages/Front/Splash.vue'
import Hero from './../components/Pages/Front/Hero.vue'
export default {
  components: {Splash, Hero},
  name: 'IndexPage'
}
</script>
