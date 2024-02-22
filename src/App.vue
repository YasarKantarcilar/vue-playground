<script setup lang="ts">
import { ref } from 'vue'
const list = ref([1, 2, 3, 4, 5, 6, 7, 8, 9, 10])
</script>

<template>
  <div class="w-full gap-4 min-h-screen bg-black grid pt-20 px-[10%] grid-cols-4">
    <div v-for="number in list" class="aspect-square bg-red-500 bg-white">
      {{ number }}
    </div>
  </div>
</template>
