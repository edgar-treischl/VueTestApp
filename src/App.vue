<template>
  <div>
    <!-- Navbar always displayed on top -->
    <Navbar />
    
    <!-- Dynamic content based on the active route -->
    <router-view />
  </div>
</template>

<script setup>
import Navbar from './components/Navbar.vue'; // Import Navbar component
</script>

<style scoped>
/* Add any styles for the app layout */
</style>
