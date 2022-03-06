<template>
  <div id="postCol" class="container-w75">

    <colOne></colOne>
    <colTwo></colTwo>
    <featuredCol></featuredCol>

  </div>
</template>

<script>

import colOne from '../assets/partials/colOne.vue'
import colTwo from '../assets/partials/colTwo.vue'
import featuredCol from '../assets/partials/featuredCol.vue'

export default {
  name: 'postCol',

  components: {
    colOne,
    colTwo,
    featuredCol,
  }
}
</script>

<style lang="scss" scoped>
  @import '../assets/style/postCol.scss';

  #postCol {
    height: 500px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
  }

</style>