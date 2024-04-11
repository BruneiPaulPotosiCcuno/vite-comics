<script>
import AppHeader from './components/AppHeader.vue';
import AppContentHere from './components/AppContentHere.vue';
import AppServices from './components/AppServices.vue'
export default {
  components: {
    AppHeader,
    AppContentHere,
    AppServices
  }
}
</script>

<template>
  <AppHeader></AppHeader>
  <ContentHere></ContentHere>
  <main>
  </main>
  <AppServices></AppServices>
</template>

<style lang="scss">
@use './style/generic';
</style>