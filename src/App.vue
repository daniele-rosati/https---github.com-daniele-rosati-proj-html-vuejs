<script>
import AppHeader from './components/AppHeader.vue';
import AppHero from './components/AppHero.vue';
import AppValues from './components/AppValues.vue';

export default {
  components: {
    AppHeader,
    AppHero,
    AppValues
  }
}
</script>

<template>
  <AppHeader></AppHeader>

  <AppHero></AppHero>

  <AppValues></AppValues>
  
</template>

<style lang="scss">
@use './style/generic';
@use './style/partiales/_variables.scss' as *;
</style>
