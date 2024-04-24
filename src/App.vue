<script>
import AppHeader from './components/AppHeader.vue';
import AppHero from './components/AppHero.vue';
import AppValues from './components/AppValues.vue';
import AppCause from './components/AppCause.vue';
import AppArticle from './components/AppArticle.vue';
import AppChange from './components/AppChange.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppHeader,
    AppHero,
    AppValues,
    AppCause,
    AppArticle,
    AppChange,
    AppFooter
  }
}
</script>

<template>
  <AppHeader></AppHeader>

  <AppHero></AppHero>

  <AppValues></AppValues>

  <AppCause></AppCause>

  <AppArticle></AppArticle>

  <AppChange></AppChange>

  <AppFooter></AppFooter>
  
</template>

<style lang="scss">
@use './style/generic';
@use './style/partiales/_variables.scss' as *;
</style>
