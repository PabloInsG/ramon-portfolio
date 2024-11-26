<script setup>
    import img1 from '../assets/foto19.jpg'
    import img2 from '../assets/foto20.jpg'
    import img3 from '../assets/foto21.jpg'
    import img4 from '../assets/foto4.jpg'
    import img5 from '../assets/foto5.jpg'
    import img6 from '../assets/foto6.jpg'
    import img7 from '../assets/foto7.jpg'
    import img8 from '../assets/foto8.jpg'
    import img9 from '../assets/foto9.jpg'
    import img10 from '../assets/foto10.jpg'
    import img11 from '../assets/foto11.jpg'
    import img12 from '../assets/foto12.jpg'
    import img13 from '../assets/foto13.jpg'
    import img14 from '../assets/foto14.jpg'
    import img15 from '../assets/foto15.jpg'
    import img16 from '../assets/foto16.jpg'
    import img17 from '../assets/foto17.jpg'
    import img18 from '../assets/foto18.jpg'
</script>

<template>
    <div class="w-full bg-[#131313] flex justify-center">
        <div className="grid grid-cols-2h-[200px] lg:grid-cols-3 grid-rows-5 gap-4 w-11/12 mt-5">
            <div class="h-[200px] lg:h-[400px]">
                <img :src="img1" class="w-full h-full" alt="">
            </div>
            <div class="h-[200px] lg:h-[400px]">
                <img :src="img2" class="w-full h-full" alt="">
            </div>
            <div class="h-[200px] lg:h-[400px]">
                <img :src="img3" class="w-full h-full " alt="">
            </div>
            <div class="lg:col-span-2 lg:row-span-2">
                <img :src="img4" class="w-full h-full" alt="">
            </div>
            <div class="h-[200px] lg:h-[400px]">
                <img :src="img5" class="w-full h-full" alt="">
            </div>
            <div class="h-[200px] lg:h-[400px]">
                <img :src="img6" class="w-full h-full " alt="">
            </div>
            <div class="h-[200px] lg:h-[400px]">
                <img :src="img7" class="w-full h-full " alt="">
            </div>
            <div class="h-[200px] lg:h-[400px]">
                <img :src="img8" class="w-full h-full " alt="">
            </div>
            <div class="h-[200px] lg:h-[400px]">
                <img :src="img9" class="w-full h-full cover" alt="">
            </div>
            <div class="h-[200px] lg:h-[400px]">
                <img :src="img10" class="w-full h-full cover" alt="">
            </div>
            <div class="h-[200px] lg:h-[400px]">
                <img :src="img11" class="w-full h-full cover" alt="">
            </div>
            <div class="h-[200px] lg:h-[400px]">
                <img :src="img12" class="w-full h-full cover" alt="">
            </div>
            <div class="h-[200px] lg:h-[400px]">
                <img :src="img13" class="w-full h-full" alt="">
            </div>
            <div class="h-[200px] lg:h-[400px]">
                <img :src="img14" class="w-full h-full" alt="">
            </div>
            <div class="h-[200px] lg:h-[400px]">
                <img :src="img15" class="w-full h-full" alt="">
            </div>
            <div class="h-[200px] lg:h-[400px]">
                <img :src="img16" class="w-full h-full" alt="">
            </div>
            <div class="h-[200px] lg:h-[400px]">
                <img :src="img17" class="w-full h-full" alt="">
            </div>
            <div class="h-[200px] lg:h-[400px]">
                <img :src="img18" class="w-full h-full" alt="">
            </div>
        </div>
    </div>
</template>

<style>
.cover {
    object-fit: fill;
}
</style>