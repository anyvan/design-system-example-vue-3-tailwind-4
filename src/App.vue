<script setup lang="ts">
import { Modal } from '@anyvan-ui/modal';
import '@anyvan-ui/checkbox/Checkbox.css';
import {defineComponent} from 'vue';
</script>

<template>
  <main>
    <h1 class="">Hello World</h1>
    <modal />
  </main>
</template>

<style>
@import '@anyvan-ui/modal/index.css';
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
