<script setup>
import AppTitle from './AppTitle.vue';
</script>

<template>
  <div class="jumbotron">
    <div class="container">
        <AppTitle/>
    </div>
  </div>
</template>

<style scoped>
.jumbotron { 
  padding: 30px; 
  background-color: #111;
}

.container {
  width: 75%; 
  margin: 0 auto;  
  padding: 0 15px; 
}

.jumbotron .container { 
  max-width: 100%; 
  background-color: #222;
}
h1{
  color: red;
}

</style>
