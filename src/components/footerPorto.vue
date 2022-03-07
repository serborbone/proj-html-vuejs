<template>
  <footer>
      <div id="footerCol">
        <div class="container-w75">
          <!-- FOOTER TOP -->
          <footerCol :colOne="colOne" :colTwo="colTwo" :colThree="colThree" :colFour="colFour"></footerCol>

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
  },

  data() {
    return {

      colOne: [
        {
          blogText: 'Lorem ipsum dolor sit amet consectetur, adipisicing elit. Natus perspiciatis ducimus accusamus perferendis quaerat cum quis eius.',
        },
        {
          blogText: 'Lorem ipsum dolor sit amet consectetur, adipisicing elit. Natus perspiciatis ducimus accusamus perferendis quaerat cum quis eius.',
        },
      ],

      colTwo: [
        {
          img: 'our-office-4-square.jpg',
          text: 'Lorem ipsum dolor sit, consectetur adipisicing elit.',
          dataHour: '12:53 AM Dec 19th',
        },
         {
          img: 'our-office-5-square.jpg',
          text: 'Lorem ipsum dolor sit, consectetur adipisicing elit.',
          dataHour: '12:53 AM Dec 19th',
        },
      ],

      colThree: [
        {
          author: 'John Doe',
          link: ' lorem ipsum dolor sit amet.',
          dataAndHour: '12.55 A Dec 19th',
        },
        {
          author: 'John Doe',
          link: ' lorem ipsum dolor sit amet.',
          dataAndHour: '12.55 A Dec 19th',
        },
      ],

      colFour: [
        {
          tag: 'Gadgets',
        },
        {
          tag: 'Photography',
        },
        {
          tag: 'Lifestyle',
        },
        {
          tag: 'Fashion',
        },
        {
          tag: 'Recipes',
        },
        {
          tag: 'Travel',
        },
        {
          tag: 'Business',
        },
        {
          tag: 'Architecture',
        },
        {
          tag: 'Reviews',
        },
        {
          tag: 'Sports',
        },
        {
          tag: 'Videos',
        },
        {
          tag: 'Technology',
        },
        {
          tag: 'Design',
        },

      ],
    }
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