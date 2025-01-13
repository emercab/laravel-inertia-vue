<template>
  <div class="">
    <h1 class="text-4xl font-bold">About Page</h1>
    <p class="mt-4">Welcome, {{ name }}</p>
  </div>
</template>

<script setup>
  defineProps({
    name: String,
  })
</script>

<style lang="css" scoped></style>