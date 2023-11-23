<script setup lang="ts"></script>

<template>
    <div id="a">
        <div class="erp">
            <button class="enter" type="submit">Войти</button>
            <button class="registration" type="submit">Регистрация</button>
            <button class="profile"><i class="fa fa-user-circle"></i></button>
        </div>
    </div>
</template>

<style scoped>
button {
    border: none;
    margin: 5px;
    border-radius: 5px;
}

button.enter {
    background-color: rgb(69, 69, 69);
    color: #fff;
}

button.registration {
    background-color: rgb(159, 0, 159);
    color: #fff;
}

button.profile {
    background-color: rgb(25, 25, 25);
}

#a {
    display: grid;
}

</style>