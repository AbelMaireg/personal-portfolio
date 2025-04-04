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
    <CardHeader>
      <h2 class="text-2xl">{{ title }}</h2>
    </CardHeader>
    <CardContent>
      <p class="text-justify px-6">{{ description }}</p>
    </CardContent>
    <CardFooter class="justify-between">
      <ExperienceLeftBottomPanel :goto="goto" :source-code="sourceCode" />
      <ExperienceTechBadges :badges="badges" />
    </CardFooter>
  </Card>
</template>
