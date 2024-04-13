<script>
import AppHeader from './components/AppHeader.vue';
import AppContentHere from './components/AppContentHere.vue';
import AppServices from './components/AppServices.vue';
import AppList from './components/AppList.vue';
import AppFooter from './components/AppFooter.vue';
import AppCards from './components/AppCards.vue';
import ComicCard from './components/ComicCard.vue';
export default {
  components: {
    AppHeader,
    AppContentHere,
    AppServices,
    AppList,
    AppFooter,
    AppCards,
    ComicCard
  }
}
</script>

<template>
  <AppHeader></AppHeader>
  <main>
    <AppContentHere>
      
    </AppContentHere>
    
    <AppCards>
      
    </AppCards>
    <AppServices></AppServices>
  </main>
  <AppList></AppList>
  <AppFooter></AppFooter>
  
</template>

<style lang="scss">
@use './style/generic';
</style>