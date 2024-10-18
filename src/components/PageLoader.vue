<template>
    <div id="page-loader" class="page-loader" v-if="!isLoaded">
        <div class="ball"></div>
        <div class="ball"></div>
        <div class="ball"></div>
        <div class="ball"></div>
    </div>
</template>

<script>
    export default {
        data: () => {
            return {
                isLoaded: false
            }
        },
        mounted()  {
            setTimeout(() => {
                this.isLoaded = true;
            }, 5000)
        }
    }
</script>

<style lang="scss" scoped>
    $colors : #ffe0b5, #ffd191, #ffc26c, #ffb444;

    .page-loader {
        display: flex;
        justify-content: center;
        align-items: center;
        position: fixed;
        top: 0;
        left: 0;
        width: 100vw;
        height: 100vh;
        background-color: #2b2b2b;
        z-index: 999;
        gap: 1em;
        transition: 0.5s;
    }

    .ball {
        width: 80px;
        height: 80px;
        border-radius: 100%;

        @for $i from 1 through length($colors) {
            &:nth-child(#{$i}) {
                background-color: nth($colors, $i );
            }
        }
        animation: wave 1.5s ease-in-out infinite;

        &:nth-child(2) {
            animation-delay: -0.2s;
        }
        &:nth-child(3) {
            animation-delay: -0.4s;
        }
        &:nth-child(4) {
            animation-delay: -0.6s;
        }
    }

        @keyframes wave {
            0%, 100% {
                transform: translateY(30px);
            }
            50% {
                transform: translateY(-30px);
            }
        }

</style>