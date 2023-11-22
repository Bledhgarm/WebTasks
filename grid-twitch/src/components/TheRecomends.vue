<script setup lang="ts">
const chanels = [
    "chanel1",
    "chanel2",
    "chanel3",
    "chanel4",
    "chanel5",
]
</script>

<template>
    <div id="recs">
        <div v-for="chanel of chanels">
            <button> {{ chanel }} </button>
        </div>
    </div>
</template>

<style scoped>
#recs {
    display: grid;
    grid-auto-rows: repeat(auto-fill);
    justify-content: center;
    align-items: center;
    border-style: dashed;
    margin-right: 2rem;
}
</style>
