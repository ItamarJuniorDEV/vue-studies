<!-- SCRIPT -->
<script setup>

// Função para validar o formulário
function validaFormulario(event) {
  alert('Formulário enviado!');

  // Com o preventDefault(), o redirecionamento não será validado  
  event.preventDefault();
}

</script>

<!-- HTML  -->
<template>
  <form action="http://itamarjr.com" @submit="validaFormulario">
    <input type="submit" value="Enviar formulário">
  </form>
</template>