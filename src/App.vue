<script>

import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';
import Jumbotron from './components/Jumbotron.vue';
import AppFooterSign from './components/AppFooterSign.vue';
import AppBlu from './components/AppBlu.vue';
import DCSeries from './components/DCSeries.vue';

export default {
  name: 'App',
  components:{
    AppHeader,
    Jumbotron,
    AppFooter,
    AppFooterSign,
    AppBlu,
    DCSeries
  }
}
</script>

<template>
  <AppHeader />
  <Jumbotron />
  <DCSeries />
  <AppBlu />
  <AppFooter />
  <AppFooterSign />
</template>


<style lang="scss">
  @use './style/general.scss'
</style>