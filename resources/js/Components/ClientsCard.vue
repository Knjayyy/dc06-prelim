<template>
    <div class="bg-gray-200 shadow-md p-2 rounded-lg mx-2">
      <div class="flex justify-center mb-2">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQwvGWjwjiCh8UCmLjeDGBj9iIZt7cyiynfwnYz_63_hg&s" alt="logo" class="max-w-sm max-h-36">
      </div>
      <h3 class="text-sm font-semibold">{{ client.last_name }}, {{ client.first_name }}</h3>
      <p class="text-gray-700 text-xs">{{ client.address }}</p>
    </div>
  </template>

  <script setup>
  const props = defineProps({
    client: Object
  });
  </script>

