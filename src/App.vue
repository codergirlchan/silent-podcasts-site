<script setup>
import HeaderNavigation from "./components/HeaderNavigation.vue";
import HeroBanner from "./components/HeroBanner.vue";
</script>

<template>
  <header>
    <HeaderNavigation />
  </header>
  <main>
    <HeroBanner />
  </main>
</template>

<style>
@import "./assets/base.css";

main {
  max-width: 1360px;
  margin: 0 auto;
}
</style>
