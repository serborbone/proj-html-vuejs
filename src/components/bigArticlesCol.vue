<template>
  <div id="bigArticlesCol">

    <div class="container-w75 col-flex">
      <div class="l-article-sect">
          <bigArticle></bigArticle>
      </div>

      <div class="r-social-sect">
          <socialCol></socialCol>
      </div>
    </div>
  </div>
</template>

<script>

import bigArticle from '../assets/partials/bigArticle.vue'
import socialCol from '../assets/partials/socialCol.vue'

export default {
  name: 'bigArticlesCol',
  components: {
    bigArticle,
    socialCol,
  }
}
</script>

<style lang="scss" scoped>
  @import '../assets/style/bigArticlesCol.scss';
</style>