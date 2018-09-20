<template>
  <section class="container">
    <Header/>
    <h2 class="subtitle">Home</h2>
    <nuxt-link to="about">About</nuxt-link>
  </section>
</template>

<script>
import Header from '~/components/Header.vue'

export default {
  components: {
    Header
  }
}
</script>
