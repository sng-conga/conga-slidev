<script setup lang="ts">
import { defineProps } from 'vue'
defineProps<{
  text: string
}>()
</script>

<template>
  <span class="text-red-500 bg-$prism-background px-2 py-1 rounded font-mono inline-block text-xs">
   {{text}}
  </span>
</template>