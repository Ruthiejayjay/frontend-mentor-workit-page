<template>
  <div class="relative">
    <Nav />
    <Header/>
    <!-- <div class="absolute -mt-16 flex justify-center" style="width: 100%; z-index: 9999;">
      <img src="./../assets/images/image-hero.webp" alt="" style="width: 50%;">
    </div> -->
    <Section />
    <Author />
  </div>
</template>

<script>
import Nav from './Nav.vue';
import Header from './Header.vue';
import Section from './Section.vue';
import Author from './Author.vue'

export default {
  components: {
    Nav,
    Header,
    Section,
    Author
  }
}
</script>