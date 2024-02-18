<template>
  <div class="antialiased">
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<script setup lang="ts">
useSeoMeta({
  title: 'Feedr',
  description: 'A simple feed reader',
});
</script>
