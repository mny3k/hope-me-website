<template>
  <div>
    <div class="image-box">
      <img src="../assets/logo.svg" alt="Vue logo" class="logo" />
      <div class="image-gradient"></div>
    </div>
    <div class="box-1">
      <h1 class="mission-statement">Mission Statement</h1>
    </div>
  </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
.box-1 {
  background-color: #1d1f3f;
  color: white;
  height: 250px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.image-box {
  background-color: #ffffff;
  color: white;
  height: 700px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.image-gradient {
  height: inherit;
  width: 100%;
  background: linear-gradient(to bottom, #00000000, #1d1f3f);
  position: absolute;
}

.logo {
  max-height: 100%;
}
</style>
