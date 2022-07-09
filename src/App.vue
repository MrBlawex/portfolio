<script setup>
import NavSec from "./sections/NavSec.vue";
import HomeSec from "./sections/HomeSec.vue";
import AboutSec from "./sections/AboutSec.vue";
import PublicationsSec from "./sections/PublicationsSec.vue";
import ProjectsSec from "./sections/ProjectsSec.vue";
import SpeechesSec from "./sections/SpeechesSec.vue";
import ActivitiesSec from "./sections/ActivitiesSec.vue";
import FooterSec from "./sections/FooterSec.vue";
</script>

<template>
  <NavSec class="bg-first" />
  <HomeSec class="bg-second" />
  <AboutSec class="bg-second" />
  <PublicationsSec class="bg-first" />
  <ProjectsSec class="bg-second" />
  <SpeechesSec class="bg-first" />
  <ActivitiesSec class="bg-second" />
  <FooterSec class="bg-first" />
</template>
