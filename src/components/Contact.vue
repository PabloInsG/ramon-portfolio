<script setup>
import Footer from './Footer.vue';
</script>

<template>
    <div class="lg:h-screen w-full text-white bg-gradient-to-b from-[#131313] to-orange-400">
        <div class="w-full lg:h-[96%]">
            <div class="flex flex-col w-full mt-20 items-center">
                <div class="w-full flex flex-col gap-y-10 ml-2">
                    <h1 class="text-2xl lg:text-5xl">¿COMO CONTACTAR <span class="bg-gradient-to-r from-orange-300 via-orange-500 to-orange-300 inline-block text-transparent bg-clip-text">CONMIGO</span>?</h1>
                    <p class="text-lg lg:text-xl">Si estás pensando en llevar a cabo un proyecto de construcción, remodelación o necesitas asesoramiento profesional para resolver cualquier problema de albañilería, ¡estoy aquí para ayudarte! No importa el tamaño o la complejidad de la obra, mi compromiso es ofrecerte una solución a la medida, eficiente y de alta calidad.</p>
                    <h2 class="text-xl lg:text-4xl">Opciones de Contacto</h2>
                    <div class="flex flex-col">
                        <span class="text-lg lg:text-xl -mt-5">- Teléfono: <span class="underline">+34 626 25 31 91</span></span>
                        <span class="text-lg lg:text-xl opacity-90">Disponible para consultas rápidas y asesoramiento inicial. Si no puedo responder de inmediato, déjame un mensaje y me pondré en contacto contigo lo antes posible.</span>
                        <span class="text-lg lg:text-xl mt-10">- WhatsApp: <span class="underline"><a href="https://wa.me/+34626253191">+34 626 25 31 91</a></span></span>
                        <span class="text-lg lg:text-xl opacity-90">Ideal para mensajes rápidos, envío de fotos de tu proyecto o recibir respuestas inmediatas. La manera más ágil de comenzar a discutir detalles y coordinar una visita.</span>
                        <span class="text-lg lg:text-xl mt-10">- Email: <span class="underline">matute.1971@hotmail.com</span></span>
                        <span class="text-lg lg:text-xl opacity-90">Perfecto para quienes prefieren detallar sus necesidades o enviar información sobre el proyecto. Prometo responder en menos de 24 horas para que tu proyecto no pierda tiempo.</span>
                    </div>                    
                </div>
            </div>
        </div>
        <Footer></Footer>
    </div>
</template>