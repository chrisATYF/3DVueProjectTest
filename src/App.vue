<script setup>
import { RouterView } from 'vue-router';
</script>

<template>
  <RouterView></RouterView>
</template>

<style>
:root {
  --dark-bg: rgba(15, 15, 15, 0.95);
  --space: 200px;
  --radius: 25px;
  --transparency: 0.8;
  font-weight: 400;
  font-style: normal;
}

body {
  overflow-x: hidden;
}
</style>