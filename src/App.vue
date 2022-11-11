<script setup>
import { ref } from "vue";

const count = ref(0);
</script>

<template>
  <main>
    <h1>Simple count</h1>
    <button @click="count++">Increase the count</button>
    <p>{{ count }}</p>
  </main>
</template>
