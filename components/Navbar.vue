<template>
  <nav class="flex justify-center space-x-8 mb-6">
    <NuxtLink to="/" class="hover:underline">Home</NuxtLink>
    <NuxtLink to="/about" class="hover:underline">About</NuxtLink>
    <NuxtLink to="/articles" class="hover:underline">Articles</NuxtLink>
    <NuxtLink to="/contact" class="hover:underline">Contact</NuxtLink>
  </nav>
</template>

<script setup>
// Pas besoin de déclarer le composant, Nuxt les importe automatiquement
</script>

<style scoped>
nav a {
  text-decoration: none;
}
nav a:hover {
  text-decoration: underline;
}
</style>
