<script>
import headerAppVue from './components/headerApp.vue';
import mainAppVue from './components/mainApp.vue';

export default {
  data() {
    return {

    }
  },
  components: {
    headerAppVue,
    mainAppVue,
  }
}
</script>

<template>
  <headerAppVue />
  <mainAppVue />
</template>

<style lang="scss">
@use "./styles/general.scss" as *;
</style>
