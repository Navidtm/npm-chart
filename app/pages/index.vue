<script setup lang="ts">
useSeoMeta({
  title: 'NPM Chart',
  ogTitle: 'NPM Chart',
  description: 'Visualize npm downloads in a beautiful chart, ready to be shared with your community.',
  ogImage: 'https://npm.chart.dev/og-image.png',
})
</script>

<template>
  <div class="grid grid-cols-2 divide-amber-500 divide-x-2 h-screen w-full justify-center">
    <NPMWelcome />
    <div class="flex flex-col items-center justify-center h-screen">
      <h1 class="text-4xl font-bold uppercase">
        Releases
      </h1>
      <p class="text-sm text-neutral-500 mt-1 text-center px-6 sm:px-0">
        Show releases npm packages
      </p>
      <UButton class="mt-2" to="/releasess">
        show releases
      </UButton>
    </div>
  </div>
</template>
