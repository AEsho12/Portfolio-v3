<script setup lang="ts">
import { RouterView } from 'vue-router'
import sidebar from './components/sidebar.vue';
import about from './components/about.vue';
import  experience from './components/experience.vue';




</script>

<template>
  <header>

    <div class="wrapper">
      
      <sidebar />
      <about />
      <experience />
      
      


    
    </div>
  </header>

  <RouterView />
</template>

<style scoped>

</style>
