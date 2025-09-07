<template>
  <header>
    <div class="wrapper">
      <img class="logo" src="../assets/Full-color-Sin-tag.png" alt="Logo" />
      <nav>
        <RouterLink to="/" exact class="nav-link">Home</RouterLink>
        <RouterLink to="/about" class="nav-link">About</RouterLink>
        <RouterLink to="/contact" class="nav-link">Contact</RouterLink>
      </nav>
    </div>
  </header>
</template>

<script setup lang="ts">
// Your TypeScript code goes here
import { RouterLink } from "vue-router";
</script>

<style scoped>
/* Your CSS styles go here */
.wrapper {
  display: flex;
  align-items: center;
  width: 100%;
  background-color: rgba(0, 0, 0, 0);
  padding: 10px;
  margin: 0;
}

.logo {
  width: auto;
  height: 100px;
  margin-right: 20px; /* Add some space between the logo and the nav */
}

nav {
  display: flex;
  gap: 15px; /* Add some space between the nav links */
  height: 100%;
}

.nav-link {
  color: white;
  text-decoration: none;
  font-family: "Gotham", sans-serif;
  font-weight: 500;
  padding: 10px;
  border-radius: 5px;
  height: 100%;
}

.nav-link:hover {
  background-color: rgba(0, 0, 0, 0.265);
  transition: all 300ms ease;
}
</style>
