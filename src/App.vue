<script>
import Navbar from './components/Navbar.vue';
import Jumbotron from './components/Jumbotron.vue';
import CTA from './components/CTA.vue';
import Cards from './components/Cards.vue';
import Footer from './components/Footer.vue';
export default{
  name: "App",
  components: {
    Navbar,
    Jumbotron,
    CTA,
    Cards,
    Footer
  },
}
</script>

<template>
 <div id="app">
  <Navbar/>
  <jumbotron/>
  <CTA/>
  <Cards/>
  <Footer></Footer>
 </div>
</template>

<style scoped>

</style>
