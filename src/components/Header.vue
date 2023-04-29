<template>
    <section class="relative w-full flex justify-center items-center overflow-hidden">
        <div class="relative z-10 mx-auto max-w-4xl text-center flex justify-center">
            <div class="">
                <img class="h-48 w-48" src="./..\assets\images\bg-pattern-1.svg" alt="">
            </div>
            <div class="w-96">
                <h1 class="text-white font-bold text-5xl pt-6 heading">Data <span
                        class="underline decoration-eucaplyptus">tailored</span>
                    to
                    your needs.</h1>
                    <Button class="mt-6 mb-12" title="Learn More" />
            
            </div> 
            <img class="h-24 w-24" src="./..\assets\images\bg-pattern-2.svg" alt="">
        </div>
    </section>
</template>

<script setup>
import Button from './Button.vue';
</script>

<style scoped>
section{
    height: 80vh;
}
section:before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: #24053E;
    border-radius: 0 0 50% 50% / 0 0 100% 100%;
    transform: scaleX(1.5);
}
</style>