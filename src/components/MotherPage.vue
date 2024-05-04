<template>
 <NavBar/>
 <HeroPage/>
 <ShowPage/>
 <ProPage/>
 <PricePage/>
 <FootPage/>
</template>

<script>
import NavBar from './NavBar.vue'
import HeroPage from './HeroPage.vue'
import ShowPage from './ShowPage.vue';
import ProPage from './ProPage.vue';
import PricePage from './PricePage.vue';
import FootPage from './FootPage.vue';

export default {
  name: 'MotherPage',
  components: {
    NavBar,
    HeroPage,
    ShowPage,
    ProPage,
    PricePage,
    FootPage
  }
 
}
</script>

<style scoped>

</style>
