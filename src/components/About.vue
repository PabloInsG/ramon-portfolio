<script setup>
import ramon from '../assets/image-removebg-preview_ramon.png'
</script>

<template>
    <div id="inicio" class="absolute inset-x-0 bottom-1/2 top-0 text-slate-600[mask-image:linear-gradient(white,transparent)]">
        <svg aria-hidden="true" class="absolute inset-0 h-full w-full">
            <defs>
                <pattern id=":Rbm:" width="128" height="128" patternUnits="userSpaceOnUse" x="50%" y="100%">
                    <path d="M0 128V.5H128" fill="none" stroke="#059669"></path>
                </pattern>
            </defs>
            <rect width="100%" height="100%" fill="url(#:Rbm:)"></rect>
        </svg>
    </div>
    <div class="w-full bg-gradient-to-b  text-white">
        <div class="flex flex-col w-full items-center justify-center h-full">
            <div class="lg:w-3/4 flex flex-col items-center mt-2 lg:items-start ">
                <v-avatar :image="ramon" alt="Ramon photo" size="220" color="#065f46"></v-avatar>
                <div class="flex flex-col bg-[#131313] z-10">
                    <h1 class="text-3xl lg:text-6xl px-1">Buenas, soy <span class="bg-gradient-to-r from-emerald-200 via-emerald-800 to-emerald-200 inline-block text-transparent bg-clip-text">Ramón Insua</span><span class="hidden lg:inline">👋🏻</span></h1>
                    <p class="mt-4 text-xl lg:text-lg px-1">Un albañil profesional con más de 25 años de experiencia en la construcción y remodelación de todo tipo de proyectos. Mi pasión es transformar ideas en realidad, desde pequeños trabajos de reparación hasta grandes proyectos de construcción.</p>
                </div>
                <div class="flex flex-col lg:flex-row mt-7 gap-y-5 w-[98%]">
                    <div class="flex flex-col lg:w-1/2 bg-emerald-800 rounded-lg lg:py-2 lg:px-2 px-1">
                        <h1 class="text-xl lg:text-4xl">Servicios que ofrezco:</h1>
                        <ul class="space-y-5 lg:text-lg">
                            <li>Reformas y remodelaciones: Mejoro espacios con acabados de alta calidad, adaptados a tus necesidades.</li>
                            <li>Revestimientos y acabados: Fachadas, pisos, y paredes con un toque profesional que eleva cualquier espacio.</li>
                            <li>Mantenimiento y reparaciones: Soluciones rápidas y eficaces para cualquier tipo de problema estructural.</li>
                        </ul>
                    </div>
                    <div class="flex flex-col lg:w-1/2 lg:ml-10 bg-emerald-800 lg:py-2 lg:px-2 px-1 rounded-lg">
                        <h1 class="text-xl lg:text-4xl">¿Por qué elegirme?</h1>
                        <ol class="space-y-5 lg:space-y-5 lg:text-lg">
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