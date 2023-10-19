<script setup>
import Images from './Images.vue';
</script>

<template>
    <!-- Hero -->
    <div class="flex flex-col-reverse gap-4 md:flex md:flex-row sm:flex-col-reverse">
        <!-- Hero Content -->
        <div class="md:w-2/3 md:p-9 md:flex md:flex-col md:justify-center">
            <h1
                class="text-5xl font-bold text-transparent md:text-5xl bg-gradient-to-r from-blue-500 via-red-500 to-purple-500 bg-clip-text md:py-4">
                UX Engineer, Nakama
            </h1>
            <p class="mt-4 text-sm leading-7 text-gray-400 md:text-base md:leading-7">
                Hi 🖐 , I'm M. Fakhrian, a Computer Science graduate from Indonesia
                passionate about crafting efficient user interfaces. I'm also an ERP
                enthusiast, merging technology and business processes for optimal
                outcomes.
            </p>

            <!-- CTA hero -->
            <div class="mt-6">
                <div class="">
                    <a href="#"
                        class="flex items-center justify-center w-full px-8 py-3 text-base font-medium text-white bg-gray-800 border border-transparent rounded-md sm:w-3/5 md:w-1/3 lg:w-1/3 hover:bg-indigo-700 md:py-2 md:text-lg md:px-10 hover:shadow">
                        Hire Me!
                    </a>
                </div>
            </div>
        </div>

        <!-- Images -->
        <div class="mx-auto md:w-1/3 md:flex md:justify-center md:items-center">
            <Images />
        </div>
    </div>
</template>