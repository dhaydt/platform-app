<template>
  <div class="home">
    <Hero />
    <Card />
  </div>
</template>

<script>
import '../assets/body.css'
import '../assets/navbar.css'
import Hero from '@/components/hero.vue'
import Card from '@/components/card.vue'

export default {
  name: 'Home',
  components: {
    Hero,
    Card
  }
}
</script>
