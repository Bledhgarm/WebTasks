<template>
    <div id="header">
        <p> Просмотр </p>
        <div id="search">
            <input type="text" />
            <input type="submit" value="поиск" />
        </div>
        <button> Войти </button>
        <button> Регистрация </button>
    </div>
</template>

<style scoped>
* {
    margin: 0;
}
#header {
    display: grid;
    grid-template-columns: 100px auto 60px 80px;
    border-style: dotted;
}

#search {
    margin: 0 auto;
}
</style>
