<script setup lang="ts">
const categories = [
    {'text': "Counter-strike 2", 'picture': "../src/assets/cs2.jpg"},
    {'text': "Dota 2", 'picture': "../src/assets/dota.jpg"},
    {'text': "Fortnite", 'picture': "../src/assets/fortnite.jpg"},
    {'text': "GTA 5", 'picture': "../src/assets/gta5.jpg"},
    {'text': "Just chatting", 'picture': "../src/assets/irl.jpg"},
    {'text': "League of legends", 'picture': "../src/assets/lol.jpg"},
    {'text': "Minecraft", 'picture': "../src/assets/minecraft.jpg"},
]
</script>

<template>
    <p>Категории, которые могут вам понравиться</p>
    <div id="categories">
        <div v-for="category of categories">
            <img :src="category.picture">
            <p>{{ category.text }}</p>
        </div>
    </div>
</template>

<style scoped>
p {
    color: #fff;
}

#categories {
    display: grid;
    grid-template-columns: repeat(auto-fill, 300px);
}
</style>