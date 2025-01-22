<script setup lang="ts">
import { RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue'

</script>

<template>
  <div class="container">
    <NavBar class="navbar"/>
    <RouterView class="router-view"/>
  </div>
</template>

<style scoped>
  .navbar {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 1000;
  }
</style>
