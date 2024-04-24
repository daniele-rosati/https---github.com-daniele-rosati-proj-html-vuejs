<script>
import AppHeader from './components/AppHeader.vue';
import AppHero from './components/AppHero.vue';

export default {
  components: {
    AppHeader,
    AppHero
  }
}
</script>

<template>
  <AppHeader></AppHeader>

  <AppHero></AppHero>
  
</template>

<style lang="scss">
@use './style/generic';
@use './style/partiales/_variables.scss' as *;
</style>
