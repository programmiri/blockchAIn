<template>
  <span class="glowing-text">blockchAIn</span>
</template>
<script setup lang="ts">
</script>
<style scoped>
.glowing-text {
  font-family: 'Courier New', monospace;
  font-size: inherit; /* Takes the font size of its parent */
  color: white;
  text-shadow: 0 0 5px rgba(173, 216, 230, 0.5),
  0 0 10px rgba(173, 216, 230, 0.5),
  0 0 15px rgba(173, 216, 230, 0.5);
  animation: glow 2s infinite alternate;
}

@keyframes glow {
  from {
    text-shadow: 0 0 5px rgba(173, 216, 230, 0.5),
    0 0 10px rgba(173, 216, 230, 0.5),
    0 0 15px rgba(173, 216, 230, 0.5);
  }
  to {
    text-shadow: 0 0 10px rgba(173, 216, 230, 1),
    0 0 15px rgba(173, 216, 230, 1),
    0 0 20px rgba(173, 216, 230, 1);
  }
}
</style>