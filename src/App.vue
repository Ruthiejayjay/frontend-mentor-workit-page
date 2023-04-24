<template>
  <div id="app">
    <LandingPage />
  </div>
</template>

<script>
import LandingPage from './components/LandingPage.vue';

export default {
  name: 'App',
  components: {
    LandingPage
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Fraunces:ital,wght@0,200;0,300;1,300;1,600&family=Manrope:wght@200;300;600&display=swap');

#app {
  font-family: Fraunces, Manrope, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  box-sizing: border-box;
}
</style>
