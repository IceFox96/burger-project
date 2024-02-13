<script setup>


import { ref } from 'vue'


</script>



<template>

<div class="center">
    <h3>Вход</h3>
    <input class="inputLogin" type="e-mail" placeholder="e-mail"/>
    <input class="inputLogin" type="password" placeholder="password"/>
    <button>Вход</button>
</div>


</template>




<style>

.center {
    
    text-align: center;
    margin: auto auto;

}

.inputLogin {

display: block;
margin: 20px auto 20px auto;

}

</style>
