<template>
  <div class="home">
    <Navmenu></Navmenu>
    <Hero></Hero>
    <Anchormenu></Anchormenu>
    <Blogsection></Blogsection>
    <Artsection></Artsection>
    <Servicessection></Servicessection>
    <Resourcesection></Resourcesection>
    <Aboutsection></Aboutsection>
    <Footer></Footer>
  </div>
</template>

<script>
  // @ is an alias to /src
import Hero from '../components/Hero.vue'
import Navmenu from '../components/Nav-menu.vue'
import Anchormenu from '../components/Anchor-menu.vue'
import Blogsection from '../components/Blog-section.vue'
import Artsection from '../components/Art-section.vue'
import Servicessection from '../components/Services-section.vue'
import Resourcesection from '../components/Resources-section.vue'
import Aboutsection from '../components/About-section.vue'
import Footer from '../components/Footer.vue'
  export default {
    name: 'Home',
    components: {Hero, Navmenu, Anchormenu, Blogsection, Artsection, Servicessection, Resourcesection, Aboutsection, Footer}
  }
</script>

<style>
html {
  scroll-behavior: smooth;
}

.section {
  height: 100vh;
}

body {
  font-size: 16px;
  color:#F4F5F6;
  background-color: #2388ff;
}

.h1, .h2, .h3, .h4, .h5, .h6, h1, h2, h3, h4, h5, h6 {
  color:#000a14;
}

a {
  color:#000a14;
}

.anchor-arrow {
  position: relative;
  bottom: 0;
  color:#000A14;
  font-size: 1rem;
  height: 100%;
}


.anchor-arrow:hover {
  color:#F4F5F6;
}

</style>