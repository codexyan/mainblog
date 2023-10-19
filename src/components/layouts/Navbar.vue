<script setup>
import { RouterLink } from "vue-router"

</script>

<template>
    <nav id="header" class="absolute w-full py-4">
        <div
            class="container relative flex flex-wrap items-center justify-between px-4 md:mx-auto md:my-4 md:max-w-7xl md:px-24">
            <!-- Logo -->
            <img src="@/assets/img/logo/logoweb.png" alt="logoweb.png" class="h-6 md:h-8">

            <!-- Navigation Link -->
            <div id="mobile-menu" class="bg-gray-900 rounded-full md:bg-gray-900 md:rounded-full">
                <ul class="flex flex-row items-center w-full gap-3 px-5 py-2 md:py-3 md:gap-5 md:px-7">
                    <li>
                        <RouterLink to="/" class="block text-xs text-white rounded md:text-sm " aria-current="page">
                            Home</RouterLink>
                    </li>
                    <li>
                        <RouterLink to="/about" class="block text-xs text-gray-600 md:text-sm">
                            About</RouterLink>
                    </li>
                    <li>
                        <RouterLink to="/blog" class="block text-xs text-gray-600 md:text-sm">
                            Blog</RouterLink>
                    </li>
                    <li>
                        <RouterLink to="/project" class="block text-xs text-gray-600 md:text-sm">
                            Project</RouterLink>
                    </li>
                </ul>
            </div>

            <!-- Auth Button -->
            <div id="cta-other" class="hidden md:inline">
                <a href="#" class="text-white">
                    IND
                </a>
            </div>
        </div>
    </nav>
</template>

<style scoped>
</style>