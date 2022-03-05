<template>
  <main>

    <section>
      <div id="jumbotron">

        <div class="container-w75">
            <cardArticle></cardArticle>
        </div>

      </div>
    </section>

  </main>
</template>

<script>

import cardArticle from './cardArticle.vue'

export default {
  name: 'mainPorto',
  components: {
    cardArticle,
  },

}
</script>

<style lang="scss" scoped>
  @import '../assets/style/mainPorto.scss';
</style>