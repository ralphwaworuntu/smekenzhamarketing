<template>
  <div class="home">
    <Header />
    <Hero />
    <Banner />
    <Instagram />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
// import carousel from 'vue-owl-carousel'
import Header from '@/components/Header.vue'
import Hero from '@/components/Hero.vue'
import Banner from '@/components/Banner.vue'
import Instagram from '@/components/Instagram.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Header,
    Hero,
    Banner,
    Instagram,
    Footer,
  }
}
</script>
