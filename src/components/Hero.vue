<template>
  <div id="hero" class=mb-5>
    <b-container class="section hero-section mb-5">
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
          <b-row align-v="baseline" class="mb-5 justify-content-center">
            <b-col cols="auto" class="w-50">
              <b-img src="../assets/image/logo.svg" alt="Logo" fluid-grow width="100%" center></b-img>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <b-link href="#menu-section">
                <b-icon align-self="end" class="anchor-arrow" icon=arrow-down font-scale=5></b-icon>
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
    width: 100% \9;
  }


</style>