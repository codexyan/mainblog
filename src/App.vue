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

  <RouterView />

  <Footer />
</template>

<style scoped>
@import "@/assets/css/styles.css";
</style>
