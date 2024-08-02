<template>
  <header>
    <header-view />
  </header>
  <main>
    <body-view />
  </main>
  <footer>
    <footer-view />
  </footer>
</template>

<script setup lang="ts">
import HeaderView from './HeaderView.vue';
import BodyView from './BodyView.vue';
import FooterView from './FooterView.vue';
</script>

<style scoped></style>
