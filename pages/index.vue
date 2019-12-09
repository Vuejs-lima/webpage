<template>
  <div>
    <Navbar />
    <Hero />
    <About />
    <Organizers />
    <Follow />
    <Footer />
  </div>
</template>

<script>
import Navbar from '~/components/Navbar'
import Hero from '~/components/Hero'
import About from '~/components/About'
import Organizers from '~/components/Organizers'
import Follow from '~/components/Follow'
import Footer from '~/components/Footer'

export default {
  components: {
    Navbar,
    Hero,
    About,
    Organizers,
    Follow,
    Footer
  }
}
</script>
