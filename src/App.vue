<script setup>
import Header from './components/Header.vue';
import Hero from './components/Hero.vue';
import Projects from './components/Projects.vue';
import Footer from './components/Footer.vue';

import AOS from 'aos';
import 'aos/dist/aos.css';

AOS.init({
  duration: 1000,
  offset: 50
});
</script>

<template>
  <div class="container">
    <Header />
    <Hero />
    <Projects />
    <Footer />
  </div>
</template>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  border: none;
  outline: none;
  list-style: none;
  text-decoration: none;
  box-sizing: border-box;
  scroll-behavior: smooth;
  transition: all 0.2s ease;
}

body {
  background-color: rgb(15, 15, 25);
}

.container {
  position: relative;
}
</style>
