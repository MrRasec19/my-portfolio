<script setup lang="ts">
import CustomDivider from '~/components/CustomDivider.vue';
import MyWork from '~/components/MyWork.vue';

</script>

<template>
    <div class="pt-10 side-space">
        <h1 class="title-font mb-3">Hi, I'm Rasec!</h1>
        <p class="body-font text-left">
            I'm a software developer specializing in building (and occasionally designing) exceptional digital experiences. Currently, I'm focused on building responsive full-stack web applications.
        </p>
    </div>
    <CustomDivider class="mt-20 mb-10">
        My Work
    </CustomDivider>
    <MyWork />
</template>