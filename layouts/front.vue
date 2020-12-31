<template>
  <section>
    <Header/>
      <Nuxt/>
    <Footer/>
  </section>
</template>

<script>
import Footer from '@/components/Footer'
import Header from '@/components/Header'
export default {
  components: {
    Footer,
    Header
  }
}
</script>

<style>

</style>