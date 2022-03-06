<template>
  <main>

    <section>
      <div id="jumbotron">

        <cardArticle></cardArticle>

      </div>
    </section>

    <section>
        <div id="post-columns">
            <postCol></postCol>
        </div>
    </section>

  </main>
</template>

<script>

import cardArticle from './cardArticle.vue'
import postCol from './postCol.vue'

export default {
  name: 'mainPorto',
  components: {
    cardArticle,
    postCol,
  },

}
</script>

<style lang="scss" scoped>
  @import '../assets/style/mainPorto.scss';
</style>