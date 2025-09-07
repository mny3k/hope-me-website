<template>
  <div>
    <div class="first-bar">
      <div class="first-bar-text">
        <h2>HOPE M&E</h2>
        <h3>Evaluation and Research</h3>
        <!-- Bird Logo on the far right -->
      </div>
    </div>
    <div class="second-bar">
      <div class="segment" id="first"></div>
      <div class="segment" id="second"></div>
      <div class="segment" id="third"></div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
.first-bar {
  background-color: var(--hope-green);
  margin: 0;
  height: 100%;
  padding: 10px;
}
h1,
h2,
h3 {
  color: white;
}

.first-bar-text {
  display: flex;
  align-items: center;
  gap: 10px;
}

.second-bar {
  height: 20px;
  display: flex;
}

.segment {
  width: 150px;
  height: 100%;
}

#first {
  background-color: #ed6c2c;
}

#second {
  background-color: #2abbdd;
}

#third {
  background-color: #907d29;
}
</style>
