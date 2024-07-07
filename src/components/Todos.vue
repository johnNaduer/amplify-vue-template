<template>
  <div>
    <form action="">
      <label for="name">Ingresar Nombre:</label>
      <input type="text" v-model="name">
      <button type="submit">enviar</button>
    </form>
  </div>
</template>

<script setup lang="ts">
import {ref} from 'vue';

const name = ref('');

</script>

<style scoped>
</style>