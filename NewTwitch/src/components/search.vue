<script setup lang="ts"></script>

<template>
    <div id="header">
        <form action="" method="" class="ButtonSearch">
            <div id="search">
                <input type="text" placeholder="Поиск">
                <button class="b-prof" type="submit"><i class="fa fa-search"></i></button>
            </div>
        </form>
        
    </div>
    
</template>

<style scoped>
button.b-prof {
    background-color: rgb(69, 69, 69);
    border: none;
    border-radius: 5px;
}

* {
    margin: 0;
}

#header {
    display: grid;
    grid-template-columns: 100px auto 60px 80px;
     
}


#search {
    margin: 0 auto;
}
</style>