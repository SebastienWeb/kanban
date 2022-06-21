<script setup>
import { RouterView } from "vue-router";
import TheWelcome from "./components/TheWelcome.vue";
</script>

<template>
  <TheWelcome />
  <main>
    <RouterView />
  </main>
</template>

<style lang="scss">
@use "@/assets/scss/base/_base.scss";
@use "@/assets/scss/utils/variables.scss";
body {
  background-color: variables.$dark-background;
}
</style>
