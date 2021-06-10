<template>
  <div id="hero" class=mb-5>
    <b-container fluid class="section hero-section mb-5">
      <b-row>
        <b-col>
          <b-row align-v=start class="p-2 mt-2">
            <b-col>
              <h1>RIVRE of SOMA</h1>
            </b-col>
          </b-row>
          <b-row class=mb-1>
            <b-col>
              <h1>Real Insights eVolve REality</h1>
            </b-col>
          </b-row>
          <b-row align-v="baseline" class="mb-n4 mb-sm-1 justify-content-center">
            <b-col cols="auto" class="logo">
              <b-img src="../assets/image/logo.svg" alt="Logo" fluid-grow center></b-img>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <b-link href="#menu-section">
                <b-icon-arrow-down align-self="end" class="anchor-arrow mb-5" font-scale=5></b-icon-arrow-down>
              </b-link>
            </b-col>
          </b-row>
        </b-col>
      </b-row>
    </b-container>

  </div>
</template>

<script>
  // @ is an alias to /src
  export default {
    name: 'Home',
    components: {

    }
  }
</script>


<style>
  .logo {
    width: 50%;
  }

  @media screen and (min-width: 576px) {
    .logo {
      width: 25%;
    }
  }

</style>