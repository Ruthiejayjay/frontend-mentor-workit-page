<template>
  <div class="relative bg-white h-96 ">
    <div class="flex flex-row justify-center mt-20">
      <div class="w-52 h-52 rounded-full bg-eucaplyptus">
        <img src="./..\assets\images\image-founder.webp" alt="">
      </div>
      <div class="w-96 h-56 -ml-12 mt-24 bg-dark-purple">
        <div class="mx-12 mt-12 text-left">
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

<script>
import Button from './Button.vue';
export default{
  components: {
    Button
  }
}
</script>