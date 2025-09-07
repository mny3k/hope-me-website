<template>
  <div class="about-page">
    <div class="about-info">
      <div class="spacer"></div>
      <h1>ABOUT US</h1>
      <h3>
        Welcome to our research firm. We specialize in providing top-notch
        research services to our clients.
      </h3>
      <p>Founded in 2024, blah blah blah</p>
    </div>
    <section class="team">
      <h2>Our Team</h2>
      <div class="team-member">
        <img class="team-image" src="../assets/MarthaPicture.jpg" />
        <div class="team-member-info">
          <h2>Martha Hernandez Martinez</h2>
          <h3>CEO</h3>
          <p>Martha is the founder, she does a lot of work, etc. etc. etc.</p>
        </div>
      </div>
      <div class="team-member">
        <img class="team-image" src="../assets/ErickPicture.jpg" />
        <div class="team-member-info">
          <h2>Erick</h2>
          <h3>Something</h3>
          <p>Erick is another founder, he does a lot of work too, etc.</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
.spacer {
  height: 120px;
}
.team {
  margin-top: 20px;
  padding-left: 40px;
  color: #333;
  margin-bottom: 20px;
}

.team-image {
  min-width: 250px;
  max-width: 250px;
  min-height: 250px;
  max-height: 250px;
  object-fit: cover;
  object-position: top;
  border-radius: 10px;
  margin: 5px;
}

.team-member {
  display: flex;
}

.team-member-info {
  margin-left: 10px;
}

.about-info {
  background-color: #296d47;
  width: 100%;
  padding: 20px;
  color: white;
  padding-bottom: 30px;
}
</style>
