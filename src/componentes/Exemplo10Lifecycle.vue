<!--
  São ações que podem acontecer em três etapas de um componente:

- Antes da criação;
- Durante a criação;
- Após a criação.

-->

<!-- SCRIPT-->
<script setup>
// Importações
import { ref, onMounted } from 'vue';

// Variável de texto
let texto = ref('Hello World!');

// Lifecycle onMounted
onMounted(() => {
  // É executado depois de um certo período
  setTimeout(() => {
    texto.value = 'Alterando texto!';
    // Vai exibir em 3000ms
  }, 3000);
});

</script>

<!-- HTML -->
<template>
  <h1>{{ texto }}</h1>
</template>