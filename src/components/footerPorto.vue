<template>
  <footer>
      <div id="footerCol">
        <div class="container-w75">
          <!-- FOOTER TOP -->
          <footerCol></footerCol>

        </div>

        <!-- FOOTER BOTTOM -->
        <div class="footer-bottom">

          <div class="container-w75 display-rules">

            <div id="logo-footer">
              <img src="../assets/img/logo-footer.png" alt="footer-logo">
            </div>

            <div class="copyright">
                <i class="fa-regular fa-copyright"></i>
                Copyright 2020. All Rights Reserved.
            </div>

            <div class="menu-foot-bottom">
                <span><i class="i-style fa-solid fa-angle-right"></i><a href="">FAQ's</a></span>
                <span><i class="i-style fa-solid fa-angle-right"></i><a href="">Sitemap</a></span>
                <span><i class="i-style fa-solid fa-angle-right"></i><a href="">Contact Us</a></span>
            </div>
          </div>

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

  @import '../assets/style/footerBottom.scss';

  #footerCol {
    height: 400px;
    background-color: #212529;
  }

</style>