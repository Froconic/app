<template>
  <div class="hero">
    <Navmenu></Navmenu>
    <b-container class="section hero-section">
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
          <b-row class=mb-5>
            <b-col>
              <b-icon class="logo-icon" icon=eye-fill font-scale=8 animation='fade'></b-icon>
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
  .logo-icon {
    align-self: center;
  }

  .anchor-arrow {
    position: relative;
    bottom: 0;
  }
</style>