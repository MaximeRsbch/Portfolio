<script setup>
import { RouterView } from "vue-router";
import Navbar from "./components/Navbar.vue";
</script>

<template>
  <div class="bg-[#11131F]">
    <Navbar />
    <RouterView />
  </div>
</template>
