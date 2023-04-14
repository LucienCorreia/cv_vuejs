<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div id="app">
    <main>
      <RouterView />
    </main>
  </div>
</template>

<style>
  @import "assets/base.css";
  
  #app {
    background-color: var(--color-primary);
    min-height: 100vh;
    width: 100vw;
    display: flex;
  }
</style>
