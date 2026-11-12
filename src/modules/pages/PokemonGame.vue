<script setup lang="ts">
import PokemonPicture from '@/modules/components/PokemonPicture.vue'
</script>

<template>
    <section v-if="true" class="flex flex-col justify-center items-center w-screen h-screen">
        <h1 class="text-3xl">Espere por favor</h1>
        <h3 class="animate-pulse">Cargando Pokemons</h3>
    </section>
    <section class="flex flex-col justify-center items-center w-screen h-screen">
        <h1>¿Who's that pokemon?</h1>
        <PokemonPicture />
    </section>
</template>

<style scoped>
</style>