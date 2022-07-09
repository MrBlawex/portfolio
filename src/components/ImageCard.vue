<template>
  <figcaption>
    <div class="profile-content">
        <img
          src="../assets/img/profile.jpg"
          alt=""
          class="img-fluid profile-img"
        />
      <div class="profile-text">
        <h1>Julien Velcin</h1>
        <h5>Professor of Computer Science</h5>
      </div>
      <Social />
    </div>
  </figcaption>
</template>

<script setup>
import Social from "../components/SocialLinks.vue";
</script>