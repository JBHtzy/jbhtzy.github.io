<script setup lang="ts">
import Navbar from "./components/Navbar.vue";
</script>

<template>
  <div>
    <Navbar />

    <div class="bg-light">
      <NuxtPage />
    </div>
  </div>
</template>

<style>
@import url("~/assets/css/style.css");
</style>
