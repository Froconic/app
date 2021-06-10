<template>
  <div class="home" id="fullpage">
    <!-- <Navmenu></Navmenu> -->
    <div class="section fullpage-section">
    <Hero></Hero>
    </div>
    <div class="section fullpage-section">
    <Anchormenu></Anchormenu>
    </div>
    <div class="section fullpage-section">
    <Blogsection></Blogsection>
    </div>
    <div class="section fullpage-section">
    <Artsection></Artsection>
    </div>
    <div class="section fullpage-section">
    <Servicessection></Servicessection>
    </div>
    <div class="section fullpage-section">
    <Resourcesection></Resourcesection>
    </div>
    <div class="section fullpage-section">
    <Aboutsection></Aboutsection>
    </div>
    <div class="section fullpage-section">
    <Footer></Footer>
    </div>
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
    components: {
      Hero,
      Navmenu,
      Anchormenu,
      Blogsection,
      Artsection,
      Servicessection,
      Resourcesection,
      Aboutsection,
      Footer
    }
  }
</script>

<style>
  html {
    scroll-behavior: smooth;
  }

  .section {
    height: 100vh;
    width: 100vw;
    margin-bottom: 0;
    overflow-x: none;
    overflow-y: scroll;
  }

  .section ::-webkit-scrollbar {
    display: none;
  }

  .fullpage-section {
    padding: 3rem;
  }

  h1,
  .h1 {
    font-weight: 700;
  }

  .h1,
  .h2,
  .h3,
  .h4,
  .h5,
  .h6,
  h1,
  h2,
  h3,
  h4,
  h5,
  h6 {
    color: #000a14;
    font-family: 'Overlock', cursive;
  }

  a {
    font-family: 'Overlock', sans-serif;
    font-weight: 700;
    color: #000a14;
  }

  .anchor-arrow {
    position: relative;
    bottom: 0;
    color: #000A14;
    font-size: 1rem;
    height: 100%;
  }


  .anchor-arrow:hover {
    color: #F4F5F6;
  }

  .card {
    background: rgba(0, 0, 0, 0.15);
    -webkit-box-shadow: 0px 0px 25px 8px rgba(0, 0, 0, 0.75);
    -moz-box-shadow: 0px 0px 25px 8px rgba(0, 0, 0, 0.75);
    box-shadow: 0px 0px 25px 8px rgba(0, 0, 0, 0.75);
    backdrop-filter: blur(12.5px);
    -webkit-backdrop-filter: blur(12.5px);
    border-radius: 10px;
    height: 100%;
  }

  .card-body {
    background: rgba(0, 0, 0, 1);
    background: -moz-linear-gradient(top, rgba(0, 0, 0, 1) 0%, rgba(112, 112, 112, 1) 0%, rgba(0, 0, 0, 0.96) 7%, rgba(255, 255, 255, 0.42) 100%);
    background: -webkit-gradient(left top, left bottom, color-stop(0%, rgba(0, 0, 0, 1)), color-stop(0%, rgba(112, 112, 112, 1)), color-stop(7%, rgba(0, 0, 0, 0.96)), color-stop(100%, rgba(255, 255, 255, 0.42)));
    background: -webkit-linear-gradient(top, rgba(0, 0, 0, 1) 0%, rgba(112, 112, 112, 1) 0%, rgba(0, 0, 0, 0.96) 7%, rgba(255, 255, 255, 0.42) 100%);
    background: -o-linear-gradient(top, rgba(0, 0, 0, 1) 0%, rgba(112, 112, 112, 1) 0%, rgba(0, 0, 0, 0.96) 7%, rgba(255, 255, 255, 0.42) 100%);
    background: -ms-linear-gradient(top, rgba(0, 0, 0, 1) 0%, rgba(112, 112, 112, 1) 0%, rgba(0, 0, 0, 0.96) 7%, rgba(255, 255, 255, 0.42) 100%);
    background: linear-gradient(to bottom, rgba(0, 0, 0, 1) 0%, rgba(112, 112, 112, 1) 0%, rgba(0, 0, 0, 0.96) 7%, rgba(255, 255, 255, 0.42) 100%);
    filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#000000', endColorstr='#ffffff', GradientType=0);
  }

  .card-title {
    color: #EBF4FF;
  }

  .card-subtitle {
    color: #001429;
  }

  .card-text {
    color: #F4F5F6;
  }

  .card-date {
    color: #F4F5F6;
  }

  .card-btn {
    color: #F4F5F6;
  }

  .col {
    height: 100%;
  }
</style>