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

    <section>
        <tagBar></tagBar>
    </section>

  </main>
</template>

<script>

import cardArticle from './cardArticle.vue'
import postCol from './postCol.vue'
import tagBar from './tagBar.vue'

export default {
  name: 'mainPorto',
  components: {
    cardArticle,
    postCol,
    tagBar,
  },

}
</script>

<style lang="scss" scoped>
  @import '../assets/style/mainPorto.scss';
</style>