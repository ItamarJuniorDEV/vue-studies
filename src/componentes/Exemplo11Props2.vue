<!-- SCRIPT -->
<script setup>

// Obter props
const props = defineProps(['nome', 'idade', 'cidade', 'cidades', 'funcao']);

</script>

<!-- HTML -->
<template>
  <h1>Nome: {{ nome }}</h1>
  <h1>Idade: {{ idade }}</h1>
  <h1>Cidade: {{ cidade }}</h1>

  <ul>
    <li v-for="cidade in cidades">{{ cidade }}</li>
  </ul>

  <button @click="funcao">Clique aqui</button>

</template>