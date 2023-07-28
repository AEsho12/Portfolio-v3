<script setup lang="ts">
import { RouterView } from 'vue-router'
import sidebar from './components/sidebar.vue';
import about from './components/about.vue';
import  experience from './components/experience.vue';
import  projects from './components/projects.vue';
import { VueElement } from 'vue';




</script>


<template>
  <header>

    <div class="wrapper">
      
      <sidebar />
      <about />
      <experience />
      <projects />
      
      


    
    </div>
  </header>

  <RouterView />
</template>

<style scoped>

</style>
