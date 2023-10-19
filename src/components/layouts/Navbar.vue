<script setup>
import { RouterLink } from "vue-router"

</script>

<template>
    <nav id="header" class="absolute w-full py-4">
        <div
            class="container relative flex flex-wrap items-center justify-between px-4 md:mx-auto md:my-4 md:max-w-7xl md:px-24">
            <!-- Logo -->
            <img src="@/assets/img/logo/logoweb.png" alt="logoweb.png" class="h-8">

            <!-- Navigation Link -->
            <div id="mobile-menu" class="bg-gray-900 rounded-full md:bg-gray-900 md:rounded-full">
                <ul class="flex flex-row items-center w-full gap-5 py-3 px-7">
                    <li>
                        <RouterLink to="/" class="block text-sm text-white rounded " aria-current="page">
                            Home</RouterLink>
                    </li>
                    <li>
                        <RouterLink to="/about" class="block text-sm text-gray-600">
                            About</RouterLink>
                    </li>
                    <li>
                        <RouterLink to="/blog" class="block text-sm text-gray-600">
                            Blog</RouterLink>
                    </li>
                    <li>
                        <RouterLink to="/project" class="block text-sm text-gray-600">
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