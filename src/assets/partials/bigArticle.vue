<template>
  <div id="bigArticle">

    <div class="article-wrap">

        <div class="img-bigart">
            <img src="../img/blog-54.jpg" alt="article image">
        </div>

        <div class="info-art">

            <div class="date-art">
                <div class="day">
                  12
                </div>
                <div class="month">
                  Jan
                </div>
            </div>

            <div class="text-art">
                <!-- TITLE -->
                <h3>How to Make Friends as a Grown-Up</h3>

                <!-- TEXT ARTICLE -->
                <p>Euismod atras vulputate iltricies etri elit. 
                Class aptent taciti sociosqu ad litora torquent per conubia nostra, 
                per inceptos himenaeos. Nulla nunc dui, tristique in semper vel, 
                congue sed ligula. Nam dolor ligula, faucibus id sodales in, 
                auctor fringilla libero. Pellentesque pellentesque tempor tellus 
                eget hendrerit. Morbi id aliquam ligula. Aliquam id dui sem. 
                Proin rhoncus consequat nisl, eu ornare mauris tincidunt vitae.[...]</p>

                <div class="info-text">

                  <span>
                    <i class="i-color fa-solid fa-user-large"></i>  
                    By <a href="#">John Doe</a></span>
                  <span>
                    <i class="i-color fa-solid fa-folder"></i> 
                    <a href="#">Lifestyle</a>, <a href="#">Travel</a>
                  </span>

                  <span>
                    <i class="i-color fa-solid fa-comments"></i>
                    <a href="#">12 Comments</a>
                  </span>

                  <!-- READ MORE BUTTON -->
                  <span class="read-btn">
                      <a href="">Read More</a>
                  </span>

                </div>
            </div>

        </div>

    </div>

  </div>
</template>

<script>
export default {
  name: 'bigArticle',
}
</script>

<style lang="scss" scoped>
  @import '../style/bigArticle.scss';
</style>