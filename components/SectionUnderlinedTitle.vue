<script setup lang="ts">
defineProps<{
  title: string;
}>();

</script>

<template>
  <div>
    <h1 class="text-2xl font-semibold text-gray-800 lg:text-3xl dark:text-white">{{ title }}</h1>

    <div class="mt-2">
      <span class="inline-block w-40 h-1 bg-blue-500 rounded-full"></span>
      <span class="inline-block w-3 h-1 ml-1 bg-blue-500 rounded-full"></span>
      <span class="inline-block w-1 h-1 ml-1 bg-blue-500 rounded-full"></span>
    </div>
  </div>
</template>
