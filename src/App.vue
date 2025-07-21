<script setup lang="ts">
import Header from './components/header.vue'
import Footer from './components/footer.vue'
</script>

<template>
  <div id="app">
    <Header />
    <router-view />
    <Footer />
  </div>
</template>

<style scoped></style>
