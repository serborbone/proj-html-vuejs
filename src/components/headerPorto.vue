<template>
  <header>
      <!-- BLUE BAR con Navbar superiore header -->
      <section id="top-nav">
        <div class="t-nav-wrap container-w75">

            <div class="top-nav-title">
                <h1>Everything about Lifestyle, Travel and Gadgets!</h1>
            </div>

            <!-- LINK MENU NAV BLU -->
            <nav>
                <div class="t-nav-li">
                    <ul>
                        <li v-for="(links, index) in blueNav" :key="index">
                            <a href="#">{{links.link}}</a>
                        </li>
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
                      <li v-for="(links, index) in btmNav" :key="index">
                          <a href="">{{links.link}}</a>
                      </li>
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

  props: {
      blueNav: Array,
      btmNav: Array,
  },
  
}
</script>

<style lang="scss" scoped>
  @import '../assets/style/headerPorto.scss';
</style>