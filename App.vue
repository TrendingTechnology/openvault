<script setup lang="ts">
import Home from './layouts/Home.vue'
</script>

<template>
  <div id="app">
    <Home />
  </div>
</template>

<style lang="css">
@tailwind base;
@tailwind components;
@tailwind utilities;

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>