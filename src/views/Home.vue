<template>
  <div class="home">
    <Nav/>
    <SectionOne/>
    <SectionTwo/>
    <SectionThree/>
    <ContactUs/>
    <Footer/>
  </div>
</template>

<script>
import Nav from '../components/Nav.vue'
import SectionOne from '../components/SectionOne.vue'
import SectionTwo from '../components/SectionTwo.vue'
import SectionThree from '../components/SectionThree.vue'
import ContactUs from '../components/ContactUs.vue'
import Footer from '../components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Nav,
    SectionOne,
    SectionTwo,
    SectionThree,
    ContactUs,
    Footer
  }
}
</script>

<style scoped>

</style>
