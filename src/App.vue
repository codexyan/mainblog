<script setup>
import { RouterView } from "vue-router"

// Component
import Navbar from "./components/layouts/Navbar.vue"
import Footer from "./components/layouts/Footer.vue";
</script>

<template>
  <header class="pb-20">
    <div>
      <Navbar />
    </div>
  </header>

  <main class="md:w-full md:py-12">
    <div class="w-auto px-4 mx-auto md:relative md:overflow-hidden md:max-w-7xl md:px-24">
      <RouterView />
    </div>
  </main>

  <Footer />
</template>

<style scoped>
@import "@/assets/css/styles.css";
</style>
