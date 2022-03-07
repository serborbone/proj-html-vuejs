<template>
  <div id="socialCol">
      <!-- TWITTER SECTION -->
      <div class="twitter-section">
          <h4>Latest from Twitter</h4>

          <div class="tweet-row">
            <i class="tw-icon fa-brands fa-twitter"></i> 
            <div class="tw-text">
              <p>If you have any suggestions for the next updates, let us know.</p>
              <span>01:05 PM Sep 18th</span>
            </div>
          </div>

          <div class="tweet-row">
            <i class="tw-icon fa-brands fa-twitter"></i> 
            <div class="tw-text">
              <p>We have just updated Porto Admin. Check the changelog for more information.</p>
              <span>01:04 PM Sep 18th</span>
            </div>
          </div>
      </div>

      <!-- INSTAGRAM SECTION -->
      <div class="instagram-section">
        <h4>Photos From Instagram</h4>

        <div class="insta-img">
            <img src="../img/29739607_2020680068220520_4509928046932787200_n.jpg" alt="instagram image">
            <img src="../img/30087804_253872848488989_8792603541668626432_n.jpg" alt="instagram image">
            <img src="../img/29415620_196477127626244_3250318472361541632_n.jpg" alt="instagram image">
            <img src="../img/30078414_1274410412703843_8290935809419247616_n.jpg" alt="instagram image">
            <img src="../img/30077195_2066750973610181_3733150062893596672_n.jpg" alt="instagram image">
            <img src="../img/29415304_166583630713703_1032667922171953152_n.jpg" alt="instagram image">
        </div>

        <h4>Tags</h4>

        <span class="tags">Design</span>
        <span class="tags">Brands</span>
        <span class="tags">Video</span>
        <span class="tags">Business</span>
        <span class="tags">Travel</span>
      </div>
  </div>
</template>

<script>
export default {
  name: 'sociaCol',
}
</script>

<style lang="scss" scoped>
  @import '../style/socialCol.scss';
</style>