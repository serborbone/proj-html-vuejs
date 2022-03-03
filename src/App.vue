<template>
  <div id="app">
    <headerPorto></headerPorto>
    <mainPorto></mainPorto>
    <footerPorto></footerPorto>
  </div>
</template>

<script>

import headerPorto from './components/headerPorto.vue'
import mainPorto from './components/mainPorto.vue'
import footerPorto from './components/footerPorto.vue'


export default {
  name: 'App',
  components: {
      headerPorto,
      mainPorto,
      footerPorto,
  }
}
</script>

<style lang="scss">

</style>
