<template>
  <div class="">
    <main class="flex items-center m-5">
      <div class="w-1/2">
        <img
          src="./assets/images/profile.png"
          alt="Portrait de l'artiste"
          class="w-full h-auto grayscale"
        />
      </div>
      <div class="summary">
        <NuxtPage />
      </div>
    </main>
    <footer class="text-white py-8 bg-gray-800 m-2">
      <Navbar />
      <p class="text-center text-gray-500">
        Copyright © 2025, Sabbat LUMPANTSHIA.
      </p>
    </footer>
  </div>
</template>

<script setup>
import { ref } from "vue";
import Navbar from "./components/Navbar.vue";
</script>

<style>
main {
  display: flex;
}
.img {
  background-color: aqua;
  height: 80vh;
  width: 100%;
}

.summary {
  background-color: beige;
  height: 80vh;
  width: 100%;
}
</style>
