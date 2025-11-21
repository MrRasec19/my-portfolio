<template>
    <TopBar />
    <div class="pt-24 px-24">
        <NuxtPage />
    </div>
    <BottomBar />
</template>

<script setup lang="ts">
import BottomBar from '~/components/BottomBar.vue';
import TopBar from '~/components/TopBar.vue';

</script>