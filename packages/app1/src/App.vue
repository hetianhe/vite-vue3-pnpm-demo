<template>
  <div>VITE_APP_API_HOST: {{ aipHost }}</div>
</template>

<script setup lang="ts">
const aipHost = import.meta.env.VITE_APP_API_HOST

console.log(aipHost)
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
