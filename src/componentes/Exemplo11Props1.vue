<!--
  PROPS -> Propriedades

  A utilização de Props fornece uma comunicação entre componentes, podemos
  enviar informações estáticas, variáveis e funções.
-->

<!-- SCRIPT -->
<script setup>

// Importar componente
import Exemplo11Props2 from './Exemplo11Props2.vue';

// Variáveis
let cidade = 'Santa Maria';
let cidades = ['Santa Maria', 'São Paulo', 'Rio de Janeiro', 'Curitiba', 'Florianópolis'];

// Função
function mensagem() {
  alert('Função criada no componente: Exemplo11Props1');
}

</script>

<!-- HTML -->
<template>
  <Exemplo11Props2 nome="Itamar" idade="28" :cidade="cidade" :cidades="cidades" :funcao="mensagem"></Exemplo11Props2>
</template>