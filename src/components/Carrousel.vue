<script setup>
import img1 from '../assets/foto1.jpg'
import img2 from '../assets/foto2.jpg'
import img3 from '../assets/foto3.jpg'
import img4 from '../assets/foto4.jpg'
import img5 from '../assets/foto5.jpg'
</script>

<template>
  <div class="h-screen flex flex-col items-center bg-[#131313]">
    <v-carousel class="!h-full !w-11/12" hide-delimiters cycle :show-arrows="false">
        <v-carousel-item :src="img1" cover></v-carousel-item>
        <v-carousel-item :src="img2" cover></v-carousel-item>
        <v-carousel-item :src="img3" cover></v-carousel-item>
    </v-carousel>
  </div>
</template>