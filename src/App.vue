<script setup lang="ts">
import { RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue'
import FooterBar from './components/FooterBar.vue';

</script>

<template>
  <div class="container">
    <NavBar class="navbar"/>
    <RouterView class="router-view"/>
    <FooterBar class="footer-bar"/>
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
  .footer-bar {
    margin: 0;
  }
</style>
