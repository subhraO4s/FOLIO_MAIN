<template>
  <Navigation />
  <Hero />
  <NAbout />
  <NAbout />
  <Faq/>
  <Footer />
</template>

<script>
import Footer from '../sections/Footer.vue'
import Hero from '../sections/Hero.vue'
import Navigation from '../sections/Navigation.vue'
import About from '../sections/About.vue'
import NAbout from '../sections/NewAbout.vue'
import Faq from "../sections/Faq.vue"
export default {
  components: {
    Hero,
    Footer,
    Navigation,
    About,
    NAbout,
    Faq
  }
}
</script>
