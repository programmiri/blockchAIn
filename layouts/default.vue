<template>
  <header class="header text-center pt-5 pb-2">
    <div class="container px-5">
      <NuxtLink to="/">
    <img src="/img/logo-light.png" aria-hidden="true" alt="" class="shadow-lg img-fluid"/>
        </NuxtLink>
    </div>
    <span class="h2 text-white bg-black px-2 rounded">scAIl your trAIning budget</span>
    <ul class="mt-3 py-2 nav nav-underline justify-content-center bg-light">
      <li class="nav-item">
        <NuxtLink class="nav-link" to="/">Start</NuxtLink>
<!--        <a class="nav-link active" aria-current="page" href="#">Active</a>-->
      </li>
      <li class="nav-item">
        <NuxtLink  class="nav-link"  to="/career">Career</NuxtLink>
      </li>
    </ul>
  </header>
  <main>
    <slot />
  </main>

  <footer class="pt-5 text-center">
    <hr />
    <p>&copy; 2023 blockchAIn</p>
  </footer>
</template>

<script setup lang="ts">
</script>

<style lang="css">
.header {
  min-height: 30vh;
  background: url("/img/header.jpeg");
  background-position: center;
}

body {
  font-size: 18px;
  font-family: "Helvetica", "Arial", sans-serif;
}
.nav a {
  color: black;
}

.nav-underline .nav-link:focus, .nav-underline .nav-link:hover {
  color: black;
}
</style>
