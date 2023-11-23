<script setup lang="ts">
import 'simplebar';
import 'simplebar/dist/simplebar.css';
const chanels = [
    "Bratishkinof",
    "Zubarefff",
    "Manyrin",
    "Zloy",
]
</script>

<template>
    <div id="block" data-simplebar data-simplebar-auto-hide="false">
        <div v-for="chanel in chanels">
            <button> {{ chanel }} </button>
        </div>

    </div>
</template>

<style scoped>

#block {
    color: #fff;
    max-width: 250px;
    max-height: 700px;
    overflow: auto;
    display: grid;
    grid-auto-rows: repeat(auto-fill);
    justify-content: center;
    align-items: center;
    border-style: dashed;
    margin-right: 2rem;
}


.simplebar-track.simplebar-vertical {
    background-color: #d9d9d9;
    width: 5px;
    
}

.simplebar-content-wrapper {
    padding-right: 30px;
}

</style>