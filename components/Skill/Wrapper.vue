<template>
  <div class="flex flex-wrap flex-row gap-12 justify-around">
    <div class="container">
      <h3>Backend frameworks and Databases</h3>
      <div class="tools backend-dev-tools">
        <IconNest class="skill-icon" />
        <IconNodejs class="skill-icon" />
        <IconBun class="skill-icon" />
        <IconPostgresql class="skill-icon" />
        <IconMysql class="skill-icon" />
        <IconMongo class="skill-icon" />
        <IconPrisma class="skill-icon" />
        <IconSpring class="skill-icon" />
      </div>
    </div>
    <div class="container">
      <h3>Frontend DevTools</h3>
      <div class="tools frontend-dev-tools">
        <IconFigma class="skill-icon" />
        <IconVue class="skill-icon" />
        <IconNuxt class="skill-icon" />
        <IconVite class="skill-icon" />
        <IconVitest class="skill-icon" />
        <IconTailwindcss class="skill-icon" />
      </div>
    </div>
    <div class="container">
      <h3>Languages</h3>
      <div class="tools lanuages">
        <IconLua class="skill-icon" />
        <IconRust class="skill-icon" />
        <IconC class="skill-icon" />
        <IconJavascript class="skill-icon" />
        <IconTypescript class="skill-icon" />
        <IconJava class="skill-icon" />
      </div>
    </div>
    <div class="container">
      <h3>Configuration tools</h3>
      <div class="tools config-tools">
        <IconGit class="skill-icon" />
        <IconUbuntu class="skill-icon" />
        <IconDocker class="skill-icon" />
        <IconNginx class="skill-icon" />
        <IconGradle class="skill-icon" />
      </div>
    </div>
  </div>
</template>

<style scoped>
.skill-icon {
  width: 108px;
  height: 108px;
}

.tools {
  display: flex;
  gap: 32px;
  flex-wrap: wrap;
}

h3 {
  font-size: 1.5rem;
  font-weight: 600;
  margin-bottom: 16px;
}
</style>
