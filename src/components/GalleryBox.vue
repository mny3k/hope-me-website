<template>
  <div class="gallery">
    <!-- Couple of images -->
     <div class="card" id="fnusa">
      <p class="card-text">"I had the pleasure of working with Martha Hernández Martínez on the Housing Training and Technical Assistance Project
at Freedom Network USA. Her collaborative approach and ability to translate evaluation and survey data into actionable
insights have helped us refine our training and technical assistance strategies, making our delivery more responsive and
effective."</p>
      <p class="card-name">- Rachel Ostergaard, Freedom Network USA</p>
     <img class="card-logo" src="../assets/FNUSALogo.png"/>
     </div>
  </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
p {
  font-size: 15px;
  text-align: center;
  font-family: "Montserrat", sans-serif;
  font-weight: 500;
  font-style: italic;
}


.card {
  display: column;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  margin-top: 50px;
  width: min-content;

  background-color: #ffffff;
  padding: 25px;
  margin: 10px;
  border-radius: 10px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

.card-logo {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 500px;
  height: auto;
}

.card-name {
  font-style: normal;
  font-weight: 700;
}

.gallery {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 20px;
}
</style>
