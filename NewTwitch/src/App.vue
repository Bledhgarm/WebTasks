<script setup lang="ts">
import search from './components/search.vue'
import auth from './components/authorization.vue'
import rec from './components/RecommendedChanels.vue'
import mainvideo from './components/MainVideo.vue'
import categories from './components/Categories.vue'
</script>

<template>
    <div id="page">
        <auth></auth>
        <search></search>
        
        <rec></rec>
        <mainvideo></mainvideo>
        <categories></categories>
    </div>
</template>

<style scoped>

#page {
    display: grid;
    grid-template-columns: 15% auto;
    margin-top: 2rem;
}
</style>
