<template>
  <main>

    <section>
      <div id="jumbotron" class="padding-section">

        <cardArticle></cardArticle>

      </div>
    </section>

    <section>
        <div class="padding-section">
            <postCol></postCol>
        </div>
    </section>

    <section>
        <tagBar></tagBar>
    </section>

    <section>
        <div class="padding-section">
            <bigArticlesCol></bigArticlesCol>
        </div>
    </section>

  </main>
</template>

<script>

import cardArticle from './cardArticle.vue'
import postCol from './postCol.vue'
import tagBar from './tagBar.vue'
import bigArticlesCol from './bigArticlesCol.vue'

export default {
  name: 'mainPorto',
  components: {
    cardArticle,
    postCol,
    tagBar,
    bigArticlesCol,
  },

}
</script>

<style lang="scss" scoped>
  @import '../assets/style/mainPorto.scss';
</style>