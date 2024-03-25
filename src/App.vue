<script setup>

import {computed, ref} from 'vue'

</script>



<template>
<div class = "mine_div">


    <div class="flexer" id="formatShapka">  

        <div class="constr_lenta">
            <button class="constr">
            <img src="../src/assets/constr.svg" alt="">
            <span>Конструктор</span>
        </button>

        <button>
            <img src="../src/assets/lenta.svg" alt="">
            Лента заказов
        </button>
        </div>


        <img class="burgerImg" src="../src/assets/burgerLogo.svg" alt="">

        <button class="lk">
            <img src="../src/assets/lk.svg" alt="">
            Личный кабинет
        </button>

    </div>
</div>

</template>




<style>

span {
    display: inline-block;
    margin-left: 3px;
    margin-top: auto;
    margin-bottom: auto;
}

.constr {
    margin-right: 10px;

}

.flexer {
    display: flex;
    padding: 10px;
}

.constr_lenta {
    display: flex;
}

.burgerImg {
    display: block;
    margin: auto;
}

.lk {
    margin-top: auto;
    margin-bottom: auto;
    margin-left: auto;
    margin-right: 0px;
}

.mine_div {
    background-color: rgb(19, 19, 22);
    display: block;
}

button {
    background-color: rgb(19, 19, 22);
    border: none;
    color: rgb(242, 242, 243);
}
/* .buttHead {
    background-color: rgb(19, 19, 22);
    border: none;
    color: rgb(242, 242, 243);
} */


</style>
