<script setup lang="ts">
import { Modal } from '@anyvan-ui/modal';
import '@anyvan-ui/modal/modal.css';
import '@anyvan-ui/button/Button.css';
</script>

<template>
  <main class="w-screen h-screen flex flex-col gap-8 items-center justify-center">
    <button class="av-button">Hello World</button>
    <modal />
  </main>
</template>

<style>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
