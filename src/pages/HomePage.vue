<template>
  <div class="home-page">
    <div class="page-container">
      <h1 class="page-title">IP-калькулятор подсетей</h1>
      <p class="page-description">
        Введите IP-адрес и выберите маску подсети для расчёта сети
      </p>
      <SubnetCalculator />
    </div>
  </div>
</template>

<script setup lang="ts">
import SubnetCalculator from '../components/SubnetCalculator.vue'
</script>

<style scoped>
.home-page {
  min-height: 100vh;
  background-color: var(--color-white); /* ← белый фон */
  padding: 50px 20px;
}

.page-container {
  max-width: 800px;
  margin: 0 auto;
}

.page-title {
  text-align: center;
  color: var(--color-primary-dark);
  font-size: 32px;
  margin-bottom: 16px;
  font-weight: 700;
}

.page-description {
  text-align: center;
  color: var(--color-text);
  font-size: 18px;
  margin-bottom: 40px;
  opacity: 0.85;
}
</style>
