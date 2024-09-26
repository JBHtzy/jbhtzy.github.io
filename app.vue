<script setup lang="ts">
import Navbar from "./components/Navbar.vue";

import "~/assets/css/style.css";
</script>

<template>
  <div>
    <Navbar />

    <div class="bg-light">
      <NuxtPage />
    </div>
  </div>
</template>
