<script setup>
    import img1 from '../assets/foto1.jpg'
    import img2 from '../assets/foto2.jpg'
    import img3 from '../assets/foto3.jpg'
    import img4 from '../assets/foto4.jpg'
    import img5 from '../assets/foto5.jpg'
</script>

<template>
    <div class="w-full bg-[#131313] flex justify-center">
        <div className="grid grid-cols-3 grid-rows-5 gap-4 w-11/12 mt-10">
            <img :src="img1" class="w-full h-full" alt="">
            <img :src="img2" class="w-full h-full" alt="">
            <img :src="img3" class="w-full h-full" alt="">
            <img :src="img4" class="w-full h-full col-span-2 row-span-2" alt="">
            <img :src="img5" class="w-full h-full" alt="">
            <img :src="img1" class="w-full h-full" alt="">
            <img :src="img2" class="w-full h-full" alt="">
            <img :src="img3" class="w-full h-full" alt="">
            <img :src="img4" class="w-full h-full" alt="">
            <img :src="img5" class="w-full h-full" alt="">
            <img :src="img3" class="w-full h-full" alt="">
            <img :src="img4" class="w-full h-full" alt="">
            <img :src="img5" class="w-full h-full" alt="">
            <img :src="img4" class="w-full h-full" alt="">
            <img :src="img3" class="w-full h-full" alt="">
        </div>
    </div>
</template>