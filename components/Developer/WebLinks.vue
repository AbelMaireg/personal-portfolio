<template>
  <div class="web-link-wrapper">
    <a href="https://github.com/AbelMaireg">
      <IconGithub class="icon" />
    </a>
    <a href="https://linkedin.com/in/AbelMaireg">
      <IconLinkedin class="icon hover:text-blue-400" />
    </a>
    <a href="https://mailto:abelrighthere@gmail.com">
      <IconMail class="icon hover:text-amber-400" />
    </a>
    <a href="https://x.com">
      <IconX class="icon" />
    </a>
    <a href="https://www.instagram.com/abel_maireg/">
      <IconMeta class="icon hover:text-blue-400" />
    </a>
    <a href="https://wa.me/237675123456">
      <IconWhatsapp class="icon hover:text-green-400" />
    </a>
    <a href="https://t.me/abelmaireg">
      <IconTelegram class="icon hover:text-sky-400" />
    </a>
  </div>
</template>

<style scoped>
.web-link-wrapper {
  margin: 0 auto;
  display: flex;
  gap: 1rem;
}

.icon {
  @apply hover:scale-200 transition-transform duration-300;
}
</style>
