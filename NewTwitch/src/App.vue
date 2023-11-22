<script setup lang="ts">
import search from './components/search.vue'
import auth from './components/authorization.vue'
import rec from './components/RecommendedChanels.vue'
import mainvideo from './components/MainVideo.vue'
import categories from './components/Categories.vue'
</script>

<template>
    <div class="page">
        <search></search>
        <auth></auth>
        <rec></rec>
        <mainvideo></mainvideo>
        <categories></categories>
    </div>
</template>

<style scoped>
div.page {
    display: grid;
    /* Три колонки */
    grid-template-columns: auto auto auto;
    /* Два ряда */
    grid-template-rows: auto auto;
    /* Автоматическое размещение в ряд */
    grid-auto-flow: row;
    /* Отступы между ячейками */
    gap: 20px;
}

</style>
