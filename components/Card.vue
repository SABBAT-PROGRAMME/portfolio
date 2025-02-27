<template>
  <div class="border p-4 rounded shadow-lg m-2">
    <h2>{{ title }}</h2>
    <p>{{ content }}</p>
  </div>
</template>

<script setup>
defineProps({
  title: String,
  content: String,
});
</script>

<style scoped>
h2 {
  color: #2c3e50;
}
</style>
