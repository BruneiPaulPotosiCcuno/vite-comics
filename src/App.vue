<script>
import AppHeader from './components/AppHeader.vue';
import AppContentHere from './components/AppContentHere.vue';
import AppServices from './components/AppServices.vue';
import AppList from './components/AppList.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  components: {
    AppHeader,
    AppContentHere,
    AppServices,
    AppList,
    AppFooter
  }
}
</script>

<template>
  <AppHeader></AppHeader>
  <main>
    <AppContentHere></AppContentHere>
    <AppServices></AppServices>
  </main>
  <AppList></AppList>
  <AppFooter></AppFooter>
</template>

<style lang="scss">
@use './style/generic';
</style>