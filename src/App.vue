<script setup>


import { ref } from 'vue'

const count = ref(0);

const input = ref('');

const sum = () => count.value ++;

</script>

<template>

<h2>Стартовая страница</h2>

<h3>{{ input }}</h3>

<input type="text" placeholder="input text" v-model="input">

<h3>{{ count }}</h3>
<button type="button" @click="sum()">+</button>
<button type="button" @click="() => count --">-</button>
<button type="button" @click="() => count = 0">clear</button>

</template>

<style>

</style>
