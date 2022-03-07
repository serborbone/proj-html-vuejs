<template>
  <div id="footerCol">
      <div class="col-one">
          <h4>About the blog</h4>

          <p v-for="(items, index) in colOne" :key="index">
            {{items.blogText}}
          </p>

          <a href="#">View More <i class="i-style fa-solid fa-angle-right"></i></a>

      </div>

      <!-- COLONNA DUE -->
      <div class="col-two">
          <h4>Recent Posts</h4>

          <div class="footer-post-row" v-for="(items, index) in colTwo" :key="index">
              <div class="img-foot-row">
                  <img src="../assets/img/our-office-4-square.jpg" alt="image recent post">
              </div>

              <div class="foot-text-post">
                  <p>{{items.text}}</p>
                  <span>{{items.dataHour}}</span>
              </div>
              
          </div>
      </div>
      <!-- FINE COLONNA DUE -->

      <!-- COLONNA TRE -->
      <div class="col-three">
          <h4>Recent Comments</h4>

          <div class="foot-comment-row" v-for="(items, index) in colThree" :key="index">

              <div class="comment">
                <i class="i-style fa-solid fa-angle-right"></i> 
                <span>{{items.author}}</span> commented on <a href="#">{{items.link}}</a>
              </div>

              <span class="h-comment">{{items.dataAndHour}}</span>

          </div>
      </div>
      <!-- FINE COLONNA TRE -->

      <!-- COLONNA QUATTRO TAG -->
      <div class="col-four">
          <h4>Categories</h4>

          <div class="tag-wrap">
            <span class="tag" v-for="(items, index) in colFour" :key="index"><a href="#">{{items.tag}}</a></span>
          </div>

      </div>
      <!-- FINE COLONNA QUATTRO TAG -->

  </div>
</template>

<script>
export default {
  name: 'footerCol',

  props: ['colOne', 'colTwo', 'colThree', 'colFour'],
}
</script>

<style lang="scss" scoped>
  @import '../assets/style/footerCol.scss';
</style>