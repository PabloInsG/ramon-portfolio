<script setup>
import MouseScroll from './components/MouseScroll.vue';
import Contact from './components/Contact.vue';
import About from './components/About.vue';
import Works from './components/Works.vue';
import Carrousel from './components/Carrousel.vue';
import Footer from './components/Footer.vue';
import Header from './components/Header.vue';
</script>
<template>
  <Header></Header>
  <div class="flex flex-col w-full bg-[#131313]">
    <div class="w-full lg:h-screen text-white justify-center items-center flex">
          <div class="d-flex flex-column fill-height justify-center align-center text-orange">
            <About></About>
            <MouseScroll/>
          </div>
    </div>
    <Carrousel></Carrousel>
    <Works></Works>
    <Contact></Contact>
    <Footer></Footer>
  </div>
</template>

<style scoped>
  html, body {
    overflow-y: hidden;
    scroll-behavior: smooth;
  }
</style>
