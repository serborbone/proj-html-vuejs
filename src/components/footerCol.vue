<template>
  <div id="footerCol">
      <div class="col-one">
          <h4>About the blog</h4>

          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Natus perspiciatis ducimus accusamus perferendis quaerat cum quis eius.</p>
          
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Natus perspiciatis ducimus accusamus perferendis quaerat cum quis eius.</p>

          <a href="#">View More <i class="i-style fa-solid fa-angle-right"></i></a>

      </div>

      <!-- COLONNA DUE -->
      <div class="col-two">
          <h4>Recent Posts</h4>

          <div class="footer-post-row">
              <div class="img-foot-row">
                  <img src="../assets/img/our-office-4-square.jpg" alt="image recent post">
              </div>

              <div class="foot-text-post">
                  <p>Lorem ipsum dolor sit, consectetur adipisicing elit.</p>
                  <span>12:53 AM Dec 19th</span>
              </div>
          </div>

          <div class="footer-post-row">
              <div class="img-foot-row">
                  <img src="../assets/img/our-office-5-square.jpg" alt="image recent post">
              </div>

              <div class="foot-text-post">
                  <p>Lorem ipsum dolor sit, consectetur adipisicing elit.</p>
                  <span>12:53 AM Dec 19th</span>
              </div>
          </div>
      </div>
      <!-- FINE COLONNA DUE -->

      <!-- COLONNA TRE -->
      <div class="col-three">
          <h4>Recent Comments</h4>

          <div class="foot-comment-row">

              <div class="comment">
                <i class="i-style fa-solid fa-angle-right"></i> 
                <span>John Doe</span> commented on <a href="#">lorem ipsum dolor sit amet.</a>
              </div>

              <span class="h-comment">12.55 A Dec 19th</span>

          </div>

          <div class="foot-comment-row">

              <div class="comment">
                <i class="i-style fa-solid fa-angle-right"></i> 
                <span>John Doe</span> commented on <a href="#">lorem ipsum dolor sit amet.</a>
              </div>

              <span class="h-comment">12.55 A Dec 19th</span>

          </div>
      </div>
      <!-- FINE COLONNA TRE -->

      <!-- COLONNA QUATTRO TAG -->
      <div class="col-four">
          <h4>Categories</h4>

          <div class="tag-wrap">
            <span class="tag"><a href="#">Gadgets</a></span>
            <span class="tag"><a href="#">Photography</a></span>
            <span class="tag"><a href="#">Lifestyle</a></span>
            <span class="tag"><a href="#">Fashion</a></span>
          </div>

      </div>
      <!-- FINE COLONNA QUATTRO TAG -->

  </div>
</template>

<script>
export default {
  name: 'footerCol',
}
</script>

<style lang="scss" scoped>
  @import '../assets/style/footerCol.scss';
</style>