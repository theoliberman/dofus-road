<template>
  <h1>💖 Hello World!</h1>
  <p>Welcome to your Electron application.</p>

  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <p>
      Edit
      <code>src/App.vue</code> to test HMR
    </p>
  </div>

  <p>
    Check out
    <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank"
      >create-vue</a
    >, the official Vue + Vite starter
  </p>
  <p>
    Install
    <a href="https://github.com/johnsoncodehk/volar" target="_blank">Volar</a>
    in your IDE for a better DX
  </p>
  <p class="read-the-docs">Click on the Vite and Vue logos to learn more</p>
</template>

<script setup>
console.log('👋 This message is being logged by "App.vue", included via Vite');

import { ref } from 'vue';

const count = ref(0);
</script>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
