<script setup lang="ts">
defineProps<{
  goto?: string
  sourceCode?: string
}>()
</script>

<template>
  <div class="flex flex-row gap-2">
    <Badge v-if="goto"><a href="https://mamitoapp.com">Open</a></Badge>
    <Badge>{{ sourceCode || "Closed Source" }}</Badge>
  </div>
</template>
