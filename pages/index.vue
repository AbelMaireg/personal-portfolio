<script setup lang="ts"></script>

<template>
  <Button
    class="bg-red-500 text-white px-4 py-2 rounded"
    @click="() => $nuxt.$router.push('/about')"
    >Hello</Button
  >
</template>
