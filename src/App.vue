<script>

import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import ContentIgnoto from './components/ContentIgnoto.vue';
import AppFooterSign from './components/AppFooterSign.vue';

export default {
  name: 'App',
  components:{
    AppHeader,
    ContentIgnoto,
    AppMain,
    AppFooter,
    AppFooterSign
  }
}
</script>

<template>
  <AppHeader />
  <ContentIgnoto />
  <AppMain />
  <AppFooter />
  <AppFooterSign />
</template>


<style lang="scss">
  @use './style/general.scss'
</style>