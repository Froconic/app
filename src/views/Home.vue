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
      <Navmenu></Navmenu>
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
          <b-icon icon=arrow-down font-scale=5></b-icon>
        </b-col>
      </b-row>
    </b-container>
    <b-container class="section services-section">
      <b-row>
        <b-col>
          <h2>Services</h2>
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <h4>Mind</h4>
          <b-row>
            <b-col>
              <h4 class="mb-0">Mind</h4>
              <b-icon-arrow-down font-scale=1.5></b-icon-arrow-down>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <h4 class="mb-0">Mind</h4>
              <b-icon-arrow-down font-scale=1.5></b-icon-arrow-down>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <h4 class="mb-0">Mind</h4>
              <b-icon-arrow-down font-scale=1.5></b-icon-arrow-down>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <h4 class="mb-0">Mind</h4>
              <b-icon-arrow-down font-scale=1.5></b-icon-arrow-down>
            </b-col>
          </b-row>
        </b-col>
        <b-col>
          <h4>Body</h4>
          <b-row>
            <b-col>
              <h4 class="mb-0">Body</h4>
              <b-icon-arrow-down font-scale=1.5></b-icon-arrow-down>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <h4 class="mb-0">Body</h4>
              <b-icon-arrow-down font-scale=1.5></b-icon-arrow-down>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <h4 class="mb-0">Body</h4>
              <b-icon-arrow-down font-scale=1.5></b-icon-arrow-down>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <h4 class="mb-0">Body</h4>
              <b-icon-arrow-down font-scale=1.5></b-icon-arrow-down>
            </b-col>
          </b-row>
        </b-col>
        <b-col>
          <h4>Soul</h4>
          <b-row>
            <b-col>
              <h4 class="mb-0">Soul</h4>
              <b-icon-arrow-down font-scale=1.5></b-icon-arrow-down>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <h4 class="mb-0">Soul</h4>
              <b-icon-arrow-down font-scale=1.5></b-icon-arrow-down>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <h4 class="mb-0">Soul</h4>
              <b-icon-arrow-down font-scale=1.5></b-icon-arrow-down>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <h4 class="mb-0">Soul</h4>
              <b-icon-arrow-down font-scale=1.5></b-icon-arrow-down>
            </b-col>
          </b-row>
        </b-col>
      </b-row>
    </b-container>
    <b-container class="section resource-section">
      <b-row>
        <b-col>
          <h2>Wellspring of Resources</h2>
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <h3 class=mb-0>Resource</h3>
          <b-icon-arrow-down font-scale="2"></b-icon-arrow-down>
        </b-col>
        <b-col>
          <h3 class=mb-0>Resource</h3>
          <b-icon-arrow-down font-scale="2"></b-icon-arrow-down>
        </b-col>
        <b-col>
          <h3 class=mb-0>Resource</h3>
          <b-icon-arrow-down font-scale="2"></b-icon-arrow-down>
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <h3 class=mb-0>Resource</h3>
          <b-icon-arrow-down font-scale="2"></b-icon-arrow-down>
        </b-col>
        <b-col>
          <h3 class=mb-0>Resource</h3>
          <b-icon-arrow-down font-scale="2"></b-icon-arrow-down>
        </b-col>
        <b-col>
          <h3 class=mb-0>Resource</h3>
          <b-icon-arrow-down font-scale="2"></b-icon-arrow-down>
        </b-col>
      </b-row>
      <b-icon-arrow-down font-scale="5"></b-icon-arrow-down>
    </b-container>
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
import Navmenu from '../components/Navmenu.vue'
  export default {
    name: 'Home',
    components: {Navmenu}
  }
</script>

<style>

</style>