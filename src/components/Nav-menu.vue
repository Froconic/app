<template>
<div class="nav-menu">
  <b-button variant="outline" v-b-toggle.sidebar-right class="sidebar-right">
    <b-img class="menu-image" src="../assets/image/menu-image.svg"></b-img>
  </b-button>
  <b-sidebar no-header id="sidebar-right" right  backdrop>
    <div id="open-menu" class="open-menu mt-3 d-flex flex-column align-items-center justify-content-center">
      <b-btn-close v-b-toggle.sidebar-right></b-btn-close>
      <b-list-group class="my-5">
          <b-list-group-item><router-link to="/">Home</router-link></b-list-group-item>
          <b-list-group-item><router-link to="/">Blog</router-link></b-list-group-item>
          <b-list-group-item><router-link to="/">Services</router-link></b-list-group-item>
          <b-list-group-item><router-link to="/">Art</router-link></b-list-group-item>
          <b-list-group-item><router-link to="/about">About</router-link></b-list-group-item>
          <b-list-group-item><router-link to="/">Contact</router-link></b-list-group-item>
          <b-list-group-item><router-link to="/">Support</router-link></b-list-group-item>
        </b-list-group>
    </div>
  </b-sidebar>
</div>
</template>

<script>
export default {
  data() {
    return {
    }
  },
}
</script>

<style>
  .nav-menu {
    position: fixed;
    right: 0%;
    top: 50%;
    z-index: 10;
  }

  .list-group-item {
    border: none;
    background: none;
  }

  .menu-image {
    width: 100px;
    height: 100px;
  }

  .b-sidebar-body, .b-sidebar-header {
    background: #2388FF;
    z-index: 100;

  }

  .close {
    z-index: 1000;
  }

  .list-group-item {
    font-size: 1.3rem;
  }
</style>