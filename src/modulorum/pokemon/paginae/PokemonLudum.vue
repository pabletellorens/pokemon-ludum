<template>
  <section v-if="false" class="flex flex-col justify-center items-center w-screen h-screen">
    <h1 class="text-3xl">Espere, por favor</h1>

    <h3 class="animate-pulse">Cargando Pokemons</h3>
  </section>

  <section class="flex flex-col justify-center items-center w-screen h-screen">
    <h1 class="m-5">¿Quién es este Pokemon?</h1>

    <PokemonImago></PokemonImago>
    <PokemonOptiones></PokemonOptiones>
  </section>
</template>

<script setup lang="ts">
import PokemonImago from '../composables/components/PokemonImago.vue';
import PokemonOptiones from '../composables/components/PokemonOptiones.vue';
</script>

<style scoped></style>
