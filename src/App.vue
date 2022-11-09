<script>
import headerAppVue from './components/headerApp.vue';
import mainAppVue from './components/mainApp.vue';
import cardsAppVue from './components/cardsApp.vue';
import footerApp from './components/footerApp.vue';
import bannerAppVue from './components/bannerApp.vue';

export default {
  data() {
    return {

    }
  },
  components: {
    headerAppVue,
    mainAppVue,
    cardsAppVue,
    footerApp,
    bannerAppVue
  }
}
</script>

<template>
  <headerAppVue />
  <bannerAppVue />
  <mainAppVue />
  <cardsAppVue />
  <footerApp />
</template>

<style lang="scss">
@use "./styles/general.scss" as *;
</style>
