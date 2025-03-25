<script setup>
import { ref } from "vue";

const numero= ref(0)
function somar() {
  numero.value++  
}
</script>

<template>
<h1>Vercel teste</h1>
<h3>atualização</h3>
<p>{{ numero }}</p>
<button @click="somar()">+</button>
</template>

<style scoped>

</style>
