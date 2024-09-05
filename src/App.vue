<template>
  <div id="app">
    <Navbar />
    <router-view/>
    <MediosPago/>
    <Footer />
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
import Footer from '@/components/Footer.vue'
import MediosPago from '@/components/MediosPago.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Footer,
    MediosPago
  }
}
</script>