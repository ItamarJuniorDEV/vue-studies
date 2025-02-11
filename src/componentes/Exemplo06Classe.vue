<!-- SCRIPT -->
<script setup>
// Variável
let validacao = false;
</script>

<!-- CSS -->
<style>
.ok {
  color: green;
}

.falha {
  color: red;
}
</style>

<!-- HTML -->
<template>
  <!-- Se a validação for verdadeira, será green; caso contrário, será red. -->
  <p :class="validacao ? 'ok' : 'falha'">Utilizando a diretiva class</p>
</template>