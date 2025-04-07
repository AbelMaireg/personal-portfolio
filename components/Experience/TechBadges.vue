<script setup lang="ts">
defineProps<{
  badges: string[]
}>()
</script>

<template>
  <div class="wrapper flex flex-row gap-2">
    <Badge v-for="badge in badges" class="bg-black">
      <IconNest v-if="badge == 'nestjs'" class="icon" />
      <IconNginx v-if="badge == 'nginx'" class="icon" />
      <IconMysql v-if="badge == 'mysql'" class="icon" />
      <IconCloudflare v-if="badge == 'cloudflare'" class="icon" />
      <IconPostgresql v-if="badge == 'postgresql'" class="icon" />
      <IconPrisma v-if="badge == 'prisma'" class="icon" />
      <IconDocker v-if="badge == 'docker'" class="icon" />
      <IconNodejs v-if="badge == 'nodejs'" class="icon" />
      <IconExpress v-if="badge == 'express'" class="icon" />
      <IconCpp v-if="badge == 'cpp'" class="icon" />
      <IconArduino v-if="badge == 'arduino'" class="icon" />
    </Badge>
  </div>
</template>

<style scoped>
.icon {
  width: 24px;
  height: 24px;
}
</style>
