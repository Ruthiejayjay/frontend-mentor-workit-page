<template>
  <div class="relative">
    <Nav />
    <Header class="z-20" />
    <div class="absolute flex justify-center -mt-28 hero" style="width: 100%; z-index: 9999;">
      <img src="./../assets/images/image-hero.webp" alt="" style="width: 40%;">
    </div>
    <Section />
    <Author />
    <Footer />
  </div>
</template>

<script setup>
import Nav from './Nav.vue';
import Header from './Header.vue';
import Section from './Section.vue';
import Author from './Author.vue'
import Footer from './Footer.vue'
</script>

<style scoped>
@media only screen and (max-width: 480px) {
  .hero {
    margin-top: -50px;
  }
}
</style>
