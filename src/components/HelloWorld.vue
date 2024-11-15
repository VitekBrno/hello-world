<script setup>
import { ref } from 'vue'

const message = ref('Hello World')
</script>

<template>
  <div class="hello-card">
    <h1>{{ message }}</h1>
    <p>Welcome to my new Vue.js application</p>
  </div>
</template>

<style scoped>
.hello-card {
  background: rgba(255, 255, 255, 0.95);
  padding: 2rem 3rem;
  border-radius: 1rem;
  box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
  text-align: center;
  backdrop-filter: blur(10px);
}

h1 {
  color: #1a1a1a;
  font-size: 3rem;
  margin: 0 0 1rem 0;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

p {
  color: #4a5568;
  font-size: 1.2rem;
  margin: 0;
}
</style>