<template>
  <section class="speeches section-gap">
    <div class="container">
      <div class="section_title">
        <h2>Recent Speeches</h2>
      </div>
      <div class="row">
        <SpeechCard />
      </div>
    </div>
  </section>
</template>

<script setup>
import SpeechCard from '../components/SpeechCard.vue'
</script>
