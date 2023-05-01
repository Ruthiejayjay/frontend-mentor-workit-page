<template>
  <div class="relative bg-white h-96 ">
    <div class="flex flex-row justify-center mt-20 author">
      <div class="w-52 h-52 rounded-full bg-eucaplyptus">
        <img src="./..\assets\images\image-founder.webp" alt="">
      </div>
      <div class="w-96 h-60 -ml-12 mt-24 bg-dark-purple author-details">
        <div class="mx-12 mt-12 text-left details-text">
          <h2 class="font-semibold text-xl text-white">Be the first to test</h2>
          <p class="my-3 text-white text-xs">Hi, I'm Louis Graham, the founder of the company. Book a demo call with me to
            become a
            beta tester for our app and kickstart your company. Apply for access below and I’ll be
            in touch to schedule a call.</p>
          <Button title="Apply for access" class="mb-3" />
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import Button from './Button.vue';
</script>

<style scoped>
/* mobile only */
@media only screen and (max-width: 480px) {
  .author {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  .author-details {
    margin: 0;
    margin-top: -40px;
    width: 288px;
  }

  .details-text {
    display: flex;
    flex-direction: column;
    text-align: center;
    margin-top: 20px;
  }
}
</style>