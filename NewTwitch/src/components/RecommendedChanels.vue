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
    <div id="component">
        <div id="block" data-simplebar data-simplebar-auto-hide="false">
            <div v-for="chanel in chanels">
                <button style="margin: auto"> {{ chanel }} </button>
            </div>
        </div>
    </div>
</template>

<style scoped>

#component {
    margin-right: 2rem;
}

#block {
    max-width: 250px;
    max-height: 700px;
    overflow: auto;
    display: grid;
    grid-auto-rows: repeat(auto-fill);
}


.simplebar-track.simplebar-vertical {
    background-color: #d9d9d9;
    width: 5px;

}

.simplebar-content-wrapper {
    padding-right: 30px;
}
</style>