<script setup lang="ts">
import ContactButton from "./ContactButton.vue";
import SocialMediaButton from "./SocialMediaButton.vue";
</script>

<template>
  <footer
    class="mt-10 bottom-0 left-0 w-full flex justify-center z-50 bg-slate-800 py-10 items-center gap-5"
  >
    <ContactButton> Get in Touch! </ContactButton>
    <a
      href="https://www.linkedin.com/in/josé-rasec-camacho-calvario-7960741ba"
      target="_blank"
      class="cursor-default"
    >
      <SocialMediaButton />
    </a>
  </footer>
</template>
