<script setup>
import ramon from '../assets/image-removebg-preview_ramon.png'
</script>

<template>
    <div class="lg:h-screen w-full bg-gradient-to-b from-[#131313] to-[#131313]  text-white">
        <div class="lg:shape w-[40rem] h-[20rem] absolute mt-60 -rotate-45 right-40"></div>
        <div class="flex flex-col w-full items-center justify-center h-full">
            <div class="lg:w-[57rem] flex flex-col items-center ml-2 lg:items-start">
                <v-avatar :image="ramon" size="220" color="orange"></v-avatar>
                <div class="flex flex-col">
                    <h1 class="text-3xl lg:text-6xl">Buenas, soy <span class="bg-gradient-to-r from-orange-300 via-orange-500 to-orange-300 inline-block text-transparent bg-clip-text">Ramon Insua</span>👋🏻</h1>
                    <p class="mt-4 opacity-90 text-xl lg:text-lg">Un albañil profesional con más de 25 años de experiencia en la construcción y remodelación de todo tipo de proyectos. Mi pasión es transformar ideas en realidad, desde pequeños trabajos de reparación hasta grandes proyectos de construcción.</p>
                </div>
                <div class="flex flex-col lg:flex-row mt-7 gap-y-5">
                    <div class="flex flex-col lg:w-1/2">
                        <h1 class="text-xl lg:text-4xl">Servicios que ofrezco:</h1>
                        <ul class="opacity-90 space-y-5 lg:text-lg">
                            <li>Reformas y remodelaciones: Mejoro espacios con acabados de alta calidad, adaptados a tus necesidades.</li>
                            <li>Revestimientos y acabados: Fachadas, pisos, y paredes con un toque profesional que eleva cualquier espacio.</li>
                            <li>Mantenimiento y reparaciones: Soluciones rápidas y eficaces para cualquier tipo de problema estructural.</li>
                        </ul>
                    </div>
                    <div class="flex flex-col lg:w-1/2 lg:ml-10">
                        <h1 class="text-xl lg:text-4xl">¿Por qué elegirme?</h1>
                        <ol class="opacity-90 space-y-5 lg:space-y-12 lg:text-lg">
                            <li>Compromiso con los plazos: Trabajo de manera eficiente para cumplir con los tiempos acordados.</li>
                            <li>Calidad garantizada: Cada proyecto está hecho con dedicación y atención al detalle.</li>
                            <li>Materiales de primera: Solo utilizo los mejores materiales para asegurar durabilidad y estética.</li>
                        </ol>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
.shape {
    background: linear-gradient(rgba(238,120,0,1) 0%,
    rgba(238,163,0,1) 77%);
    border-radius: 25rem 25rem 0 0;
    opacity: 0.7;
}
</style>