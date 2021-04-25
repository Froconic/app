<template>
  <div class="home">
    <b-container class="section hero-section">
      <b-row>
        <b-col>
          <b-row>
            <b-col>
              <h1>RIVRE of SOMA</h1>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <h1>Real Insights eVolve REality</h1>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <b-icon icon=eye-fill font-scale=8 animation='fade'></b-icon>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <b-icon icon=arrow-down font-scale=5></b-icon>
            </b-col>
          </b-row>
        </b-col>
      </b-row>
      <b-button class=menu>Menu</b-button>
    </b-container>
    <b-container class="section menu-section">
      <b-row align-h="between">
        <b-col>
          <b-link to= />Services</b-link>
        </b-col>
        <b-col>
          <b-link to= />Blog</b-link>
        </b-col>
      </b-row>
      <b-row align-h="center">
        <b-col>
          <b-link to= />About</b-link>
        </b-col>
      </b-row>
      <b-row align-h="between">
        <b-col>
          <b-link to= />Art</b-link>
        </b-col>
        <b-col>
          <b-link to= />Wellspring</b-link>
        </b-col>
      </b-row>
      <b-row align-h="center">
        <b-icon-arrow-down font-scale=5></b-icon-arrow-down>
      </b-row>
    </b-container>
    <b-container class="section blog-section">
      <b-row align-h=center>
        <b-col>
          <h2>Blog</h2>
        </b-col>
      </b-row>
      <b-row class=mb-5>
        <b-col>
          <h3>Featured</h3>
          <b-row>
            <b-col>
              <b-card title=Title sub-title=Category>
                <h6>Date</h6>
                <b-button variant=outline>
                  <b-icon-box-arrow-in-right></b-icon-box-arrow-in-right>
                </b-button>
              </b-card>
            </b-col>
          </b-row>
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <b-card title=Title sub-title=Category>
            <h6>Date</h6>
            <b-button variant=outline>
              <b-icon-box-arrow-in-right></b-icon-box-arrow-in-right>
            </b-button>
          </b-card>
        </b-col>
        <b-col>
          <b-card title=Title sub-title=Category>
            <h6>Date</h6>
            <b-button variant=outline>
              <b-icon-box-arrow-in-right></b-icon-box-arrow-in-right>
            </b-button>
          </b-card>
        </b-col>
        <b-col>
          <b-card title=Title sub-title=Category>
            <h6>Date</h6>
            <b-button variant=outline>
              <b-icon-box-arrow-in-right></b-icon-box-arrow-in-right>
            </b-button>
          </b-card>
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <b-icon-arrow-down></b-icon-arrow-down>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
  // @ is an alias to /src

  export default {
    name: 'Home',
    components: {}
  }
</script>

<style>
  .menu {
    position: fixed;
    right: 0%;
    top: 50%
  }
</style>