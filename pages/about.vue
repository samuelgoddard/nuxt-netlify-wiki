<template>
  <section class="container">
    <Header />
    <h2 class="subtitle">About</h2>
    <nuxt-link to="/">Home</nuxt-link>
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
