<!-- SCRIPT -->
<script setup>
// Variável
let texto = 'Aprendendo a diretiva v-html'; 
</script>

<!-- HTML -->
<template>

  <!-- Usado apenas em estruturas HTML -->
  <div v-html="texto"></div>

  <!-- Usado no retorno de dados -->
  <div>{{ texto }}</div>
</template>
