<template>
  <HomePage />
</template>

<script setup lang="ts">
import HomePage from './pages/HomePage.vue'
</script>

<style>
:root {
  --color-primary: #ff6b9d;
  --color-primary-dark: #e03a70;
  --color-success: #3ddc97;
  --color-error: #ff6b6b;
  --color-white: #ffffff;
  --color-text: #4a4a4a;
  --color-border: #f0d4de;
  --color-background: #ffffff;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.6;
  color: var(--color-text);
  background-color: var(--color-background);
}
</style>
