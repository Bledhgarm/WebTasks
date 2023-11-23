<script setup lang="ts">
import search from './components/search.vue'
import auth from './components/authorization.vue'
import rec from './components/RecommendedChanels.vue'
import mainvideo from './components/MainVideo.vue'
import categories from './components/Categories.vue'
</script>

<template>
    <div id="header">
        <search id="search"></search>
        <auth></auth>
    </div>
    <div id="page">
        <rec></rec>
        <div>
            <mainvideo></mainvideo>
            <categories></categories>
        </div>
    </div>
</template>

<style scoped>
#page {
    display: grid;
    grid-template-columns: 15% auto;
    margin-top: 2rem;
}

#header {
    display: grid;
    grid-template-columns: auto 200px;
}

#search {
    margin: 0 auto;
}
</style>
