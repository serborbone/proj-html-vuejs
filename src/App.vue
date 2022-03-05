<template>
  <div id="app">
    <headerPorto :blueNav="headerTopNav" :btmNav="headerBottomNav"></headerPorto>
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
  },

  data() {
    return {
       
       //TOP MENU blu NAV header
       headerTopNav: [

          {
            link: 'Sign in',
          },
          {
            link: 'About us',
          },
          {
            link: 'Contact us',
          },
          {
            link: 'Buy now',
          },

       ],
       
       //BOTTOM MENU NAV Header
       headerBottomNav: [
          {
            link: 'Home',
          },
          {
            link: 'Elements',
          },
          {
            link: 'Features',
          },
          {
            link: 'Pages',
          },
          {
            link: 'Portfolio',
          },
          {
            link: 'Blog',
          },
          {
            link: 'Shop',
          },
       ],
    }
  }
}
</script>

<style lang="scss">
  @import './assets/style/general.scss';
  @import './assets/style/variablesPorto.scss';
</style>
