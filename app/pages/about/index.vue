<template>
  <div class="pt-10 side-space mb-12">
    <h1 class="title-font text-7xl">About Me</h1>
  </div>
  <MyProfile />
  <CustomDivider class="mt-20 mb-10">Work Time Line </CustomDivider>
  <WorkTimeLine />
  <CustomDivider class="mt-20 mb-10">My Hobbies</CustomDivider>
  <div class="pt-5 px-12 mb-12">
    <h1 class="title-font text-4xl sm:text-5xl md:text-6xl lg:text-7xl">When i'm outside code</h1>
  </div>
  <MoreAboutMe />
</template>

<script setup lang="ts">
import MoreAboutMe from "~/components/MoreAboutMe.vue";
import MyProfile from "~/components/MyProfile.vue";
import WorkTimeLine from "~/components/WorkTimeLine.vue";
</script>
