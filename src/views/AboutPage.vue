<template>
  <div class="about-page">
    <div class="about-info">
      <div class="spacer"></div>
      <h1>ABOUT US</h1>
      <h3>
        Hope M&E is a bilingual Latino-Led organization based
        in Minnesota, <br> specializing in evaluation and research with
        services offered locally and nationally.
      </h3>
      <p>
        Founded in 2024, we believe that evaluation and research should equip staff, <br>
        founders, leaders, beneficiaries, and community members to make <br>
        informed decisions that effectively address the challenges they face.
      </p>
    </div>
    <section class="team">
      <h2>Our Team</h2>
      <div class="team-member">
        <img class="team-image" src="../assets/MarthaPicture.jpg" />
        <div class="team-member-info">
          <h2>Martha Hernandez Martinez</h2>
          <h3>CEO</h3>
          <p>Martha is the Founder and CEO of Hope M&E Evaluation and Research LLC.,
            a bilingual expert with over two decades of experience driving social change
            as a researcher, evaluator, and advocate. <br>
            Originally from Nicaragua, her career spans national work as a trainer,
            community organizer, and policy advocate, giving her a unique, ground-level
            perspectiveon community transformation. <br>
            Her specialized research and advocacy focus on critical issues including
            intimate partner violence, masculinities, human trafficking, and the impact
            of public policy on women's lives. She is deeply committed to creating tangible
            change in gender-based violence prevention, community development,
            women’s entrepreneurship, and housing equity. <br>
            A published thought leader, her work has appeared in renowned journals such
            as New Directions for Evaluation, Women & Therapy, Psychology of Violence,
            and the Journal of Family Violence. <br>
            Martha holds a Master of Public Affairs from the University of Minnesota and a
            Licensure in Psychology from the National Autonomous University of Nicaragua.
            This blend of academic rigor and grassroots experience establishes her as a
            trusted and innovative leader in her field.</p>
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
