<script setup lang="ts">
defineProps<{
  title: string
  description: string
  badges: string[]
}>()
</script>

<template>
  <Card>
    <CardHeader>{{ title }}</CardHeader>
    <CardContent>{{ description }}</CardContent>
    <CardFooter class="justify-end">
      <ExperienceTechBadges :badges="badges" />
    </CardFooter>
  </Card>
</template>
