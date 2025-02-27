<template>
  <nav class="bg-blue-500 p-4 text-white">
    <NuxtLink to="/" class="mr-4">Accueil</NuxtLink>
    <NuxtLink to="/about" class="mr-4">À Propos</NuxtLink>
    <NuxtLink to="/contact" class="mr-4">Contact</NuxtLink>
    <NuxtLink to="/articles" class="mr-4">Articles</NuxtLink>
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
