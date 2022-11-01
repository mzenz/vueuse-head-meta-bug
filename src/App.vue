<template>
  <span>Hello Vite</span>
</template>

<script setup lang="ts">
import { useHead } from '@vueuse/head'

const meta = [
  { property: 'article:tag', content: 'tag1' },
  { property: 'article:tag', content: 'tag2' },
]

console.debug(meta)

useHead({ title: 'Hello Vite', meta })
</script>
