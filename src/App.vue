<script setup>

import {computed, ref} from 'vue'

</script>



<template>
<div class = "mine_div">
    <div>
        <!-- <span>
            <a href=""><img src="../src/assets/constr.svg" alt=""> Конструктор</a>
        </span>
        <span>
            <a href=""> <img src="../src/assets/lenta.svg" alt=""> Лента заказов</a>
        </span>
        <img src="../src/assets/burgerLogo.svg" alt="">
        <span>
            <a href=""><img src="../src/assets/lk.svg" alt=""> Личный кабинет</a>
        </span> -->

        <button class="buttHead">
            <img src="../src/assets/constr.svg" alt="">
            Конструктор
        </button>

        <button class="buttHead">
            <img src="../src/assets/lenta.svg" alt="">
            Лента заказов
        </button>

        <img src="../src/assets/burgerLogo.svg" alt="">

        <button class="buttHead">
            <img src="../src/assets/lk.svg" alt="">
            Личный кабинет
        </button>

    </div>
</div>

</template>




<style>

.mine_div {
    background-color: rgb(19, 19, 22);
    display: block;
}

.buttHead {
    background-color: rgb(19, 19, 22);
    border: none;
    color: rgb(242, 242, 243);
}


</style>
