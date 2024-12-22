<template>
  <div id="proyectos" class="flex flex-col items-center border-none bg-[#131313]">
    <h1 class="uppercase text-5xl text-white lg:text-8xl mt-16">Proyectos<span class="text-emerald-600">.</span></h1>
    <v-carousel class="!h-full lg:!h-[47rem] !w-11/12 lg:!w-3/4 border-none mt-3" hide-delimiters cycle :show-arrows="false">
        <v-carousel-item :src="img1" alt="first image carrousel" cover></v-carousel-item>
        <v-carousel-item :src="img2" alt="second image carrousel" cover></v-carousel-item>
        <v-carousel-item :src="img3" alt="third image carrousel" cover></v-carousel-item>
    </v-carousel>
    <svg v-if="!isMobile"  class="arrows mt-8 mb-8">
        <path class="a1" d="M0 0 L30 32 L60 0"></path>
        <path class="a2" d="M0 20 L30 52 L60 20"></path>
        <path class="a3" d="M0 40 L30 72 L60 40"></path>
    </svg>
  </div>
</template>

<script setup>
import img1 from '../assets/foto1.jpg'
import img2 from '../assets/foto2.jpg'
import img3 from '../assets/foto3.jpg'

import { ref, onMounted, onUnmounted } from "vue";

const isMobile = ref(false);

// Verificar el estado con media query
const checkViewport = () => {
  isMobile.value = window.matchMedia("(max-width: 768px)").matches;
};

onMounted(() => {
  checkViewport();
  window.addEventListener("resize", checkViewport);
});

onUnmounted(() => {
  window.removeEventListener("resize", checkViewport);
});
</script>