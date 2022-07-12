<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
import HomePage from './components/HomePage.vue'
</script>

<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3 + TypeScript + Vite" /> -->
  <HomePage class="mainFrame"></HomePage>
</template>

<style>
#app {
height: 100%;
}

html,body{
  height: 100%;
  margin: unset;
}

.mainFrame{
  height: 100%;
  background-color: #000;
}
</style>
