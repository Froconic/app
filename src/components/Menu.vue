<template>
  <div class="menu">
    <b-button class="outline" v-b-toggle.sidebar-right>Menu</b-button>
    <b-sidebar id="sidebar-right" title="Menu" right shadow>
      <div class="open-menu">
        <b-list-group>
          <b-list-group-item><b-link to="/">Home</b-link></b-list-group-item>
          <b-list-group-item><b-link to="/">Blog</b-link></b-list-group-item>
          <b-list-group-item><b-link to="/">Services</b-link></b-list-group-item>
          <b-list-group-item><b-link to="/">Art</b-link></b-list-group-item>
          <b-list-group-item><b-link to="/">Contact</b-link></b-list-group-item>
          <b-list-group-item><b-link to="/">Support</b-link></b-list-group-item>
        </b-list-group>
      </div>
    </b-sidebar>
  </div>
</template>

<script>
export default {
  
}
</script>

<style>
    .menu {
    position: fixed;
    right: 0%;
    top: 50%
  }

</style>