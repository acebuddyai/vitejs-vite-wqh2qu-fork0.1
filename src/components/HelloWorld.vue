<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <p>
      Edit
      <code>components/HelloWorld.vue</code> to test HMR
    </p>
  </div>

  <p>
    Welcome to the AceBuddy Project!
  </p>
  <p>
    This is your starting point for building the AceBuddy application.
  </p>
  <p class="read-the-docs">Click on the Vite and Vue logos to learn more about the technologies used</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>