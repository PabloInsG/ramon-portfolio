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

    const images = [
        img5,
        img6,
        img7,
        img8,
        img9,
        img10,
        img11,
        img12,
        img13,
        img14,
        img15,
        img16,
        img17,
        img18,
    ]
</script>

<template>
    <div class="w-full bg-[#131313] flex justify-center">
        <div className="grid lg:grid-cols-3 grid-rows-5 gap-4 w-11/12 lg:w-3/4 mt-5">
            <div class="h-[200px] lg:h-[325px]">
                <img :src="img1" class="w-full h-full cover" alt="First image">
            </div>
            <div class="h-[200px] lg:h-[325px]">
                <img :src="img2" class="w-full h-full" alt="Second image">
            </div>
            <div class="h-[200px] lg:h-[325px]">
                <img :src="img3" class="w-full h-full " alt="Third image">
            </div>
            <div class="lg:col-span-2 lg:row-span-2">
                <img :src="img4" class="w-full h-full" alt="Fourth image">
            </div>
            <div v-for="image in images" class="h-[200px] lg:h-[325px]">
                <img :src="image" class="w-full h-full " alt="Third image"> 
            </div>
        </div>
    </div>
</template>

<style>
.cover {
    object-fit:cover;
}
</style>