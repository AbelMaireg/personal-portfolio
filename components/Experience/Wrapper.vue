<script setup lang="ts">
const experiences = [
  {
    title: "Mamito",
    description:
      "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Enim animi sapiente magnam, numquam maxime asperiores nulla, expedita consequuntur incidunt assumenda, obcaecati voluptatem illo eveniet fugiat? Libero beatae aliquam quis vero.",
    badges: ["Nestjs", "Nginx", "MySQL"],
  },

  {
    title: "Endeavour",
    description:
      "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Enim animi sapiente magnam, numquam maxime asperiores nulla, expedita consequuntur incidunt assumenda, obcaecati voluptatem illo eveniet fugiat? Libero beatae aliquam quis vero.",
    badges: ["Nestjs", "Nginx", "MySQL"],
  },
]
</script>

<template>
  <div class="flex flex-col gap-4 py-4">
    <p class="text-4xl">Experiences</p>
    <div class="flex flex-col gap-2">
      <ExperienceCard
        v-for="{ title, description, badges } in experiences"
        :title="title"
        :description="description"
        :badges="badges"
      />
    </div>
  </div>
</template>
