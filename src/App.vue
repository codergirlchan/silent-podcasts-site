<script setup>
import HeaderNavigation from "./components/HeaderNavigation.vue";
import HeroBanner from "./components/HeroBanner.vue";
import PodcastPlayerWrapper from "./components/PodcastPlayer/PodcastPlayerWrapper.vue";
import EpisodeLinks from "./components/EpisodeLinks.vue";
import FooterNavigation from "./components/FooterNavigation.vue";
</script>

<template>
  <header>
    <HeaderNavigation />
  </header>
  <main>
    <HeroBanner />
    <PodcastPlayerWrapper />
    <EpisodeLinks />
  </main>
  <FooterNavigation />
</template>

<style scoped>
main {
  max-width: 1200px;
  margin: 0 auto;
}
</style>
