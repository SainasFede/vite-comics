<script>

import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';
import ContentIgnoto from './components/ContentIgnoto.vue';
import AppFooterSign from './components/AppFooterSign.vue';
import AppBlu from './components/AppBlu.vue';

export default {
  name: 'App',
  components:{
    AppHeader,
    ContentIgnoto,
    AppFooter,
    AppFooterSign,
    AppBlu
  }
}
</script>

<template>
  <AppHeader />
  <ContentIgnoto />
  <AppBlu />
  <AppFooter />
  <AppFooterSign />
</template>


<style lang="scss">
  @use './style/general.scss'
</style>