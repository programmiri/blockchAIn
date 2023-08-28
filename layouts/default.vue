<template>
  <header>
    <h1>Welcome</h1>
    <nav>
      <ul>
        <li><a href="#">start</a></li>
        <li><a href="#">about</a></li>
        <li><a href="#">jobs</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <slot />
  </main>

  <aside>
    <h2>News</h2>
    <article>
      <h3>Our Angel investors</h3>
      <p>Read about them</p>
    </article>

    <article>
      <h3>Founders</h3>
      <p></p>
    </article>
  </aside>

  <footer>
    <p>&copy; 2023 blockchAin</p>
  </footer>

</template>
<script setup lang="ts">
</script>