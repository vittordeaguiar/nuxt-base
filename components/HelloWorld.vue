<script setup lang="ts">
import { ref } from 'vue'
const message = ref('Hello, Vue!')
</script>

<template>
  <main class="w-full min-h-screen flex justify-center items-center debug">
    <h1 class="text-4xl font-semibold">{{ message }}</h1>
  </main>
</template>
