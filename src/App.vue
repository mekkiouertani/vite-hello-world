<script setup>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
import AppImage from './components/AppImage.vue';
</script>

<template>
  
  <header>
    <h2>test</h2>
    <AppTitle/>
  </header>

  <main>
    <AppImage/>
    <AppHero/>
    <AppImage/>
  </main>
  
</template>

<style>
main{
  justify-content: center;
  display: flex;
  align-items: center;
}

</style>
