<template>
  <div>
    <div class="image-box">
      <img src="../assets/IMG_1737.JPEG" alt="Banner Image" class="banner" />
      <div class="image-gradient"></div>
      <div class="image-text-box">
        <h1 class="image-text">CREATE</h1>
        <h1 class="image-text">RESOLVE</h1>
        <h1 class="image-text">IMPACT</h1>
      </div>
    </div>
    <div class="box-1">
      <h1 class="mission-statement">
        Humanizing the World of Evaluation and Research
      </h1>
    </div>
    <div class="box-2">
      <p>
        At Hope M&E, we believe evaluation and research should equip staff,
        founders, leaders, beneficiaries, and community members to make informed
        decisions that effectively address the challenges they face.
      </p>
      <GalleryBox />
    </div>
    <div class="box-3">
      <h1 class="review-text">To humanize evaluation and research processes</h1>
      <h3>Our Mission</h3>
    </div>
  </div>
</template>

<script setup lang="ts">
import GalleryBox from "@/components/GalleryBox.vue";
</script>

<style scoped>
.box-1 {
  background-color: #296d47;
  color: white;
  height: 250px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.box-2 {
  padding: 50px;
}

.box-3 {
  background-color: var(--hope-gold);
  color: white;
  padding: 50px;
  text-align: center;
}

.review-text {
  font-size: 65px;
}

.image-box {
  background-color: #ffffff;
  color: white;
  height: 800px;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 1;
}

.image-gradient {
  height: inherit;
  transition: cubic-bezier();
  width: 100%;
  background: linear-gradient(to bottom, #00000000, #296d47);
  position: absolute;
}

.banner {
  max-height: 100%;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.image-text {
  font-size: 10vw;
  margin: 0;
  user-select: none;
}

.image-text-box {
  position: absolute;
  right: 30px;
  text-align: right;
}
</style>
