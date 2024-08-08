<script lang="ts">
import Banner from './components/Banner.vue';
import ConteudoPrincipal from './components/ConteudoPrincipal.vue';
import SelecionarIngredientes from './components/SelecionarIngredientes.vue';
import Rodape from "@/components/Rodape.vue";

export default {
  components: {Rodape, Banner, ConteudoPrincipal, SelecionarIngredientes }
}
</script>

<template>
  <Banner />
  <ConteudoPrincipal />
  <Rodape />
</template>