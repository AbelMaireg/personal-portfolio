<script setup lang="ts">
defineProps<{
  title: string
  description: string
  badges: string[]
  goto?: string
  sourceCode?: string
}>()
</script>

<template>
  <Card>
    <CardHeader>{{ title }}</CardHeader>
    <CardContent>{{ description }}</CardContent>
    <CardFooter class="justify-between mr-3">
      <ExperienceLeftBottomPanel :goto="goto" :source-code="sourceCode" />
      <ExperienceTechBadges :badges="badges" />
    </CardFooter>
  </Card>
</template>
