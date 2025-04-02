<script setup lang="ts">
defineProps<{
  badges: string[]
}>()
</script>

<template>
  <div class="wrapper flex flex-row gap-2">
    <Badge v-for="badge in badges" class="">{{ badge }}</Badge>
  </div>
</template>

<style scoped></style>
