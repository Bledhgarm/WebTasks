<script setup lang="ts"></script>

<template>
    <div id="component">
        <form action="" method="" class="ButtonSearch">
            <input type="text" placeholder="Поиск">
            <button type="submit"><i class="fa fa-search"></i></button>
        </form>
    </div>
</template>

<style scoped>
button {
    background-color: rgb(69, 69, 69);
    border: none;
    border-radius: 5px;
}

button:hover {
    background-color: red;
}

#component {
    margin: 0 auto;
}
</style>