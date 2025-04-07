<script setup lang="ts">
import Prisma from "../Icon/Prisma.vue"

const experiences = [
  {
    title: "Mamito",
    description:
      "The app that brings people together based on their current mood and location. Whether you're feeling happy, sad, angry, surprised, bored, or sick, Mamito connects you with others who share your emotional state. The unique algorithm matches you with individuals nearby, making it easy to find someone who understands you.",
    badges: ["nestjs", "nginx", "mysql", "prisma", "docker"],
    goto: "https://play.google.com/store/apps/details?id=com.mamito.app&pcampaignid=web_share",
  },

  {
    title: "Endeavour",
    description:
      "A job portal website for connecting job seekers and employers. It allows users to create profiles, upload resumes, and apply for jobs. Employers can post job listings and search for candidates. The platform aims to streamline the hiring process and make it easier for both job seekers and employers to find the right match. The platform also support recruitment agencies so they can manage their clients and candidates.",
    badges: ["nodejs", "express", "mysql"],
  },

  {
    title: "Automated Traffic Flow Management",
    description:
      "A project that aims to improve traffic flow and reduce congestion in urban areas. The system uses real-time data from traffic sensors to analyze traffic patterns and adjust traffic signals accordingly. The goal is to optimize traffic flow, reduce travel times, and improve overall road safety.",
    badges: ["cpp", "arduino"],
    sourceCode:
      "https://github.com/AbelMaireg/automated-traffic-flow-management",
    goto: "https://sites.google.com/view/ietpgroup78/home",
  },
]
</script>

<template>
  <div class="flex flex-col gap-4 py-4">
    <p class="text-4xl">Experiences</p>
    <div class="flex flex-col gap-2">
      <ExperienceCard
        v-for="{ title, description, badges, goto, sourceCode } in experiences"
        :title="title"
        :description="description"
        :badges="badges"
        :goto="goto"
        :source-code="sourceCode"
      />
    </div>
  </div>
</template>
