<script setup lang="ts">
import { FccButton, useHelloWorld } from "vue3-npm-publish-boilerplate";
import "vue3-npm-publish-boilerplate/style.css";
const test = useHelloWorld();

console.log({ test });
// import { FccButton } from 'test-component-lib'
// import "test-component-lib/style.css"
</script>

<template>
  <FccButton text="Run the Tests" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
