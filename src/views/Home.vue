<template>
  <div class="home">
    <!-- Page Preloder -->
    <!-- <div id="preloder">
        <div class="loader"></div>
    </div> -->
    <Header></Header>
    <Hero></Hero>
    <Product></Product>
    <Social></Social>
    <Partner></Partner>
    <Footer></Footer>
     
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue"
import Hero from "@/components/Hero.vue"
import Product from "@/components/Product.vue"
import Social from "@/components/Social.vue"
import Partner from "@/components/Partner.vue"
import Footer from "@/components/Footer.vue"

export default {
  name: 'Home',
  components: {
    Header,
    Hero,
    Product,
    Social,
    Partner,
    Footer

  }
}
</script>
