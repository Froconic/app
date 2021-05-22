<template>
  <div class="nav-menu">
    <b-button class="outline" v-b-toggle.sidebar-right>Menu</b-button>
    <b-sidebar no-header z-index="100" id="sidebar-right" right backdrop-variant shadow lg>
      <div class="open-menu mt-3 d-flex flex-column align-items-center justify-content-center" v-show="open">
        <button v-b-toggle.sidebar-right><b-btn-close class="close" v-b-toggle.sidebar-right></b-btn-close></button>
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
  data() {
    return {
      open: false
    }
  },

    methods: {
      // toggleMenu() {
      //   this.open = !this.open
      // },

      close (e) {
        if (!this.$el.contains(e.target)) {
          this.open = false
        }
      }
    },
    mounted () {
      document.addEventListener('click',this.close)
    },
    beforeDestroy () {
      document.removeEventListener('click',this.close)
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

  .close {
    z-index: 1000;
  }
</style>