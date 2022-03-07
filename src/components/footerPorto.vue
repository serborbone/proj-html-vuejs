<template>
  <footer>
      <div id="footerCol">
        <div class="container-w75">
          <footerCol></footerCol>
        </div>
      </div>
  </footer>
</template>

<script>

import footerCol from './footerCol.vue'

export default {
  name: 'footerPorto',

  components: {
    footerCol,
  }
}
</script>

<style lang="scss" scoped>

  #footerCol {
    height: 500px;
    background-color: #1c2023;
  }

</style>