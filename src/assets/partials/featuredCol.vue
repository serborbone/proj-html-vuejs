<template>
  <div id="featuredCol">

    <h3>Featured Posts</h3>

    <!-- CARD FEATURED POSTS -->
    <div class="card-feat">

        <div class="text-wrap">
              <span class="tag-article">Recipes</span>
              <h4><a href="#">Tips to Help You Quickly Prepare your Lunch</a></h4>
        </div>

        <img src="../img/blog-66.jpg" alt="img featured post">
    
    </div>

    <!-- FEATURED AUTHOR -->
    <div class="feat-author">
        <h3>Featured Author</h3>
        
        <div class="author-wrap">
            
            <div class="author-img">
                <img src="../img/avatar.jpg" alt="author image">
            </div>

            <div class="info-author">
              <h4><a href="#">John Doe</a></h4>

              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam viverra euismod odio
                gravida pelle, consectetur adipiscing elit.</p>
            </div>
        </div>

    </div>

  </div>
</template>

<script>
export default {
  name: 'featuredCol'
}
</script>

<style lang="scss" scoped>

  @import '../style/featuredCol.scss';

</style>