<!--
A simple wrapper for embeded Spotify videos
Usage:
<Spotify id="luoMHjh-XcQ" />
-->

<script setup lang="ts">
import { defineProps } from 'vue'
defineProps<{
  id: string
  width?: number
  height?: number
}>()
</script>

<template>
  <iframe
    :width="width"
    :height="height"
    :src="`https://open.spotify.com/embed/track/${id}`"
    frameborder="0"
    allow="encrypted-media"
    allowtransparency="true" 
  ></iframe>
</template>
