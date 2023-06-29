<script setup>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

components:{
  AppHeader,
  AppMain,
  AppFooter
}
</script>

<template>
  <div id="page">
    <AppHeader />
    <AppMain />
    <AppFooter />
  </div>
  
</template>


<style lang="scss">
@import './style/general.scss';

#page{
  width: 100vw;
  height: 100vh;
  
}
</style>