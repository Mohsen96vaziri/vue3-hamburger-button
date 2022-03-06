<script lang="ts">
import { defineComponent } from 'vue';
import Vue3HamburgerButton from '@/vue3-hamburger-button.vue';

export default defineComponent({
  name: 'ServeDev',
  components: {
    Vue3HamburgerButton
  }
});
</script>

<template>
  <div id="app">
    <vue3-hamburger-button />
  </div>
</template>
