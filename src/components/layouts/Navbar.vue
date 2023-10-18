<script setup>
import { RouterLink } from "vue-router"
</script>

<template>
    <nav id="header" class="absolute w-full py-4">
        <div class="container relative flex flex-wrap items-center justify-between px-8 md:mx-auto md:my-4 md:max-w-7xl md:px-24">
            <!-- Logo -->
            <img src="@/assets/img/logo/logoweb.png" alt="logoweb.png" class="h-8">
            
            <!-- Navigation Link -->
            <div class="hidden md:inline md:bg-gray-900 md:rounded-full">
                <ul class="flex flex-row items-center w-full px-4 py-3">
                    <li>
                        <RouterLink to="/" 
                            class="block pl-3 pr-4 text-sm text-white rounded "
                            aria-current="page">
                            Home</RouterLink>
                    </li>
                    <li>
                        <RouterLink to="/about" 
                            class="block pl-3 pr-4 text-sm text-gray-600">
                            About</RouterLink>
                    </li>
                    <li>
                        <RouterLink to="/blog" 
                            class="block pl-3 pr-4 text-sm text-gray-600">
                            Blog</RouterLink>
                    </li>
                    <li>
                        <RouterLink to="/project" 
                            class="block pl-3 pr-4 text-sm text-gray-600">
                            Project</RouterLink>
                    </li>
                </ul>
            </div>

            <!-- Auth Button -->
            <div class="">
                <a href="#" class="text-white">
                    IND
                </a>
            </div>
        </div>
    </nav>
</template>

<style scoped>
</style>