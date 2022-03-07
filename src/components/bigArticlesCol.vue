<template>
  <div id="bigArticlesCol">

    <div class="container-w75 col-flex">
      <div class="l-article-sect">
          <bigArticle></bigArticle>
      </div>

      <div class="r-social-sect">
      </div>
    </div>
  </div>
</template>

<script>

import bigArticle from '../assets/partials/bigArticle.vue'

export default {
  name: 'bigArticlesCol',
  components: {
    bigArticle,
  }
}
</script>

<style lang="scss" scoped>
  @import '../assets/style/bigArticlesCol.scss';
</style>