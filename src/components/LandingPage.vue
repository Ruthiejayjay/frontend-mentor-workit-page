<template>
  <div class="relative">
    <Nav />
    <Header />
    <div class="absolute">
      <img src="./../assets/images/image-hero.webp" alt="">
    </div>
    
  </div>
</template>

<script>
import Nav from './Nav.vue';
import Header from './Header.vue';

export default {
  components: {
    Nav,
    Header
  }
}
</script>