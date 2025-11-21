<template>
  <div class="fixed top-4 left-0 w-full flex justify-center z-50">
    <div
      class="navbar bg-slate-800 lg:max-w-1/2 w-full rounded-full shadow-xl/5 shadow-slate-100 flex justify-around items-baseline"
    >
      <NuxtLink to="/" class="cursor-default">
        <div class="avatar avatar-placeholder hover:shadow-2xl transition-all hover:scale-105">
          <div class="bg-neutral text-neutral-content w-15 rounded-full">
            <span class="text-xl font-extrabold">RC</span>
          </div>
        </div>
      </NuxtLink>
      <NuxtLink
        to="/"
        class="text-xl hover:underline hover:font-extrabold cursor-default hover:scale-105 transition-all"
      >
        Work
      </NuxtLink
      >
      <NuxtLink
        to="/about"
        class="text-xl hover:underline hover:font-extrabold cursor-default hover:scale-105 transition-all"
        >About</NuxtLink
      >
      <a
        href="/CV_JoseRasecCamachoCalvario.pdf"
        target="_blank"
        class="text-xl hover:underline hover:font-extrabold cursor-default hover:scale-105 transition-all"
        >Resume</a
      >
      <ContactButton class="sm:block hidden" />
    </div>
  </div>
</template>

<script setup lang="ts">
import ContactButton from "./ContactButton.vue";
</script>
