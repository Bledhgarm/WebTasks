<script setup lang="ts">
import TheHeader from './components/TheHeader.vue';
import TheRecomends from './components/TheRecomends.vue';
import TheViewport from './components/TheViewport.vue'
</script>

<template>
  <TheHeader />
  <div id="page">
    <TheRecomends />
    <TheViewport />
  </div>
</template>

<style scoped>
#page {
  display: grid;
  grid-template-columns: 15% auto;
  margin-top: 2rem;
}
</style>
