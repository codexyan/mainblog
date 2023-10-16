<script setup>
import { RouterView } from "vue-router"

// Component
import Navbar from "./components/layouts/Navbar.vue"
</script>

<template>
  <header class="pb-20">
    <div>
      <Navbar />
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
@import "@/assets/css/styles.css";
</style>
