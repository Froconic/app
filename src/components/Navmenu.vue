<template>
  <div class="nav-menu">
    <b-button class="outline" v-b-toggle.sidebar-right>Menu</b-button>
    <b-sidebar close-label z-index="100" id="sidebar-right" right backdrop shadow>
      <div class="open-menu mt-3">
        <b-list-group>
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
  data: function () {
    props: {

    }
  }
}
</script>

<style>
  .nav-menu {
    position: fixed;
    right: 0%;
    top: 50%
  }

  .list-group-item{
    border: none;
    background: none;
  }

  .b-sidebar-body, .b-sidebar-header {
    background: #74888D;
  }

  .open-menu {
    z-index: 10;
  }

</style>