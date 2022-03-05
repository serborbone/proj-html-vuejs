<template>
  <header>
      <!-- BLUE BAR con Navbar superiore header -->
      <section id="top-nav">
        <div class="t-nav-wrap container-w75">

            <div class="top-nav-title">
                <h1>Everything about Lifestyle, Travel and Gadgets!</h1>
            </div>

            <!-- Link Menu nav blu -->
            <nav>
                <div class="t-nav-li">
                    <ul>
                        <li><a href="#">Sign In</a></li>
                        <li><a href="#">About Us</a></li>
                        <li><a href="#">Contact Us</a></li>
                        <li><a href="#">Buy Now</a></li>
                    </ul>
                </div>
            </nav>

        </div>
      </section>

      <!-- LOGO PORTO -->
      <section>
          <div id="logo-section">

              <div class="container-w75">
                  <img src="../assets/img/logo-default-slim.png" alt="logo Porto">
              </div>

          </div>
      </section>

      <!-- MENU NAV con Searchbar -->
      <section>
          <div id="bottom-nav" class="container-w75">

              <div class="left-nav-link">
                  <ul>
                      <li><a href="">Home</a></li>
                      <li><a href="">Elements</a></li>
                      <li><a href="">Features</a></li>
                      <li><a href="">Pages</a></li>
                      <li><a href="">Portfolio</a></li>
                      <li><a href="">Blog</a></li>
                      <li><a href="">Shop</a></li>
                  </ul>
              </div>

              <div class="right-searchbar">
                  <i class="pos-icon fa-solid fa-magnifying-glass"></i>
                  <input type="search">
              </div>

          </div>
      </section>
      
  </header>
</template>

<script>
export default {
  name: 'headerPorto',
}
</script>

<style lang="scss" scoped>
  @import '../assets/style/headerPorto.scss';
</style>