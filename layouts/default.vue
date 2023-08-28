
<template>
  <html data-bs-theme="dark">
    <header class="header text-center pt-5">
      <span class="display-1 text-white bg-black px-2 rounded">blockchAIn</span>
      <br />
      <br />
      <span class="h2 text-white bg-black px-2 rounded">scAIl your trAIning budget</span>
    </header>
    <main>
      <slot />
    </main>

    <footer>
      <p>&copy; 2023 blockchAin</p>
    </footer>
  </html>
</template>

<script setup lang="ts">
</script>

<style lang="css">
.header {
  height: 30vh;
  background: url("/img/header.jpeg");
  background-position: center;
}
</style>