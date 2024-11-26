<script setup>
import PageLoader from './components/PageLoader.vue';
import MouseScroll from './components/MouseScroll.vue';
import Contact from './components/Contact.vue';
import About from './components/About.vue';
import Works from './components/Works.vue';
import Carrousel from './components/Carrousel.vue';
import logoLab from './assets/logo_def.png'
</script>
<template>
  <div class="flex flex-col w-full">
    <PageLoader/> 
    <div class="w-full h-screen bg-gray-500 text-white text-9xl justify-center items-center flex">
        <v-parallax class="h-screen w-full bg-gradient-to-b from-orange-400 to-[#131313]">
          <div class="d-flex flex-column fill-height justify-center align-center text-orange">
            <img :src="logoLab" class="lg:w-1/4" alt="">
            <h1 class="text-5xl lg:text-9xl text-white">RAMON INSUA</h1>
            <MouseScroll/>
          </div>
        </v-parallax>
    </div>
    <About></About>
    <Carrousel></Carrousel>
    <Works></Works>
    <Contact></Contact>
  </div>
</template>

<style scoped>
  html, body {
    overflow-y: hidden;
  }
</style>
