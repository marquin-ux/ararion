<script setup>
import { onMounted } from 'vue'

onMounted(() => {
  document.documentElement.classList.add('scroll-smooth')
})
</script>

<template>
  <RouterView />
</template>

<style scoped>
html {
  scroll-behavior: smooth;
}
</style>
