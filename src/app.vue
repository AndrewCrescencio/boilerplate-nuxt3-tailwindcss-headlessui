<script lang="ts" setup>
// Use SSR-safe IDs for Headless UI - see https://nuxt.com/modules/headlessui#quick-setup
provideHeadlessUseId(() => useId())
</script>
<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>
