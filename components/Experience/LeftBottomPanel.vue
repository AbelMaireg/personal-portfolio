<script setup lang="ts">
defineProps<{
  goto?: string
  sourceCode?: string
}>()
</script>

<template>
  <div class="flex flex-row gap-2">
    <Badge v-if="goto"><a :href="goto">Open</a></Badge>

    <Badge v-if="sourceCode"
      ><a href="https://github.com/AbelMaireg/automated-traffic-flow-management"
        >Goto</a
      ></Badge
    >
    <Badge v-else>Closed</Badge>
  </div>
</template>
