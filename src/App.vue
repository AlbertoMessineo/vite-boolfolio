<script>
import AppHeader from './components/AppHeader.vue';
import AppMainVue from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: "vite-boolfolio",
  components:{
    AppHeader,
    AppMainVue,
    AppFooter


  }
};
</script>

<template>
  <AppHeader/>
  <AppMainVue/>
  <AppFooter/>
</template>

<style scoped></style>
