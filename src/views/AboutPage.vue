<template>
  <div class="about-page">
    <h1>About Us</h1>
    <p>Welcome to our research firm. We specialize in providing top-notch research services to our clients.</p>
    <section class="team">
      <h2>Our Team</h2>
      <ul>
        <li v-for="member in team" :key="member.id">
          <h3>{{ member.name }}</h3>
          <p>{{ member.role }}</p>
        </li>
      </ul>
    </section>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue';

interface TeamMember {
  id: number;
  name: string;
  role: string;
}

const team = ref<TeamMember[]>([
  { id: 1, name: 'Alice Johnson', role: 'Lead Researcher' },
  { id: 2, name: 'Bob Smith', role: 'Data Analyst' },
  { id: 3, name: 'Charlie Brown', role: 'Research Assistant' }
]);
</script>

<style scoped>
.about-page {
  padding: 20px;
}

.team {
  margin-top: 20px;
}

h1, h2, h3 {
  color: #333;
}

p {
  color: #666;
}
</style>
