<script setup lang="ts">
import AsideLeft from '@/components/AsideLeft.vue';
import AsideRight from '@/components/AsideRight.vue';
import Resume from '@/components/Resume.vue';

</script>

<template>
  <div id="home">
    <AsideLeft></AsideLeft>
    <Resume></Resume>
    <AsideRight></AsideRight>
  </div>
</template>

<style>
  #home {
    min-height: 100vh;
    height: 100%;
    display: flex;
    flex-direction: row;
    align-items: start;
    justify-content: start;
    width: 100vw;
  }
</style>
