<template>
  <div class="home">
    <Navmenu></Navmenu>
    <Hero></Hero>
    <Anchormenu></Anchormenu>
    <Blogsection></Blogsection>
    <Servicessection></Servicessection>
    <Resourcesection></Resourcesection>

    <b-container class="section about-section">
      <b-row>
        <b-col><img src="" alt=""></b-col>
        <b-col>
          <h3>What is RIVRE of SOMA</h3>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Iusto minima eum nam numquam cupiditate nobis cumque sunt nulla adipisci iste consequatur nostrum rem itaque ex, beatae quidem quam dolor veritatis.</p>
        </b-col>
      </b-row>
      <b-icon-arrow-down font-scale="5"></b-icon-arrow-down>
    </b-container>
    <b-container class="section footer-section">
      <b-row>
        <b-col>
          <b-link to=/>Support</b-link>
        </b-col>
        <b-col>
          <b-link to=/>Blog</b-link>
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <b-link to="/">Contact</b-link>
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <b-link to="/">Art</b-link>
        </b-col>
        <b-col>
          <h6>Copyright Froconic Design 2021</h6>
        </b-col>
        <b-col>
          <b-icon-arrow-up font-scale="2"></b-icon-arrow-up>
        </b-col>
        <b-col>
          <h6>Handcrafted By Froconic Design</h6>
        </b-col>
        <b-col>
          <b-link to="/">Wellspring</b-link>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
  // @ is an alias to /src
import Hero from '../components/Hero.vue'
import Navmenu from '../components/Nav-menu.vue'
import Anchormenu from '../components/Anchor-menu.vue'
import Blogsection from '../components/Blog-section.vue'
import Servicessection from '../components/Services-section.vue'
import Resourcesection from '../components/Resources-section.vue'
  export default {
    name: 'Home',
    components: {Hero, Navmenu, Anchormenu, Blogsection, Servicessection, Resourcesection}
  }
</script>

<style>
.section {
  height: 100vh;
}
</style>