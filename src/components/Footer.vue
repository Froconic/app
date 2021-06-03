<template>
  <b-container fluid id="footer" class="section footer-section">
    <b-container fluid class="footer-container">
      <b-row>
        <b-col class="upper-left-link">
          <b-link to="/">Support</b-link>
        </b-col>
        <b-col class="upper-right-link">
          <b-link to="/">Blog</b-link>
        </b-col>
      </b-row>
      <b-row>
        <b-col align-v=center align-h=center class="middle-link">
          <b-link to="/">Contact</b-link>
        </b-col>
      </b-row>
      <b-row >
        <b-col class="bottom-left-link">
          <b-link to="/">Art</b-link>
        </b-col>
        <b-col class="left-copyright">
          <span>Copyright Froconic Design <b-icon-dash-circle font-scale=".5"></b-icon-dash-circle> 2021</span>
        </b-col>
        <b-col class="footer-arrow">
          <b-link href="#hero">
            <b-icon-arrow-up align-self="end" class="anchor-arrow" font-scale="2"></b-icon-arrow-up>
          </b-link>
        </b-col>
        <b-col class="right-copyright">
          <span>Handcrafted By <b-link href="https://akiraallen.com/">Froconic Design</b-link></span>
        </b-col>
        <b-col class="bottom-right-link">
          <b-link to="/">Wellspring</b-link>
        </b-col>
      </b-row>
    </b-container>
  </b-container>

</template>

<script>
  export default {

  }
</script>

<style>
  .section.footer-section {
    height: 40vh;
  }

  .footer-container {
    position: relative;
    height: 100%;
    font-size: 2rem;
  }

  .upper-left-link.col {
    position: absolute;
    top: 0;
    left: 0;
    width: 40%;
}

  .upper-right-link.col {
    position: absolute;
    top: 0;
    right: 0;
    width: 40%;
}

  .bottom-left-link.col {
    position: absolute;
    bottom: 10%;
    left: 0;
    width: 40%;
}

  .bottom-right-link.col {
    position: absolute;
    bottom: 10%;
    right: 0;
    width: 40%;
}

.middle-link {
  position: absolute;
  top: 25%;
  bottom: 25%;
  
}

.right-copyright {
  position: absolute;
  bottom: 0;
  right: 20%;
  width: 20%;
}

.right-copyright span {
  font-size: .8rem;
}

.left-copyright {
  position: absolute;
  bottom: 0;
  left: 20%;
  width: 20%;
}

.left-copyright span {
  font-size: .8rem;
}


.footer-arrow {
  position: absolute;
  bottom: 0;
  right: 25%;
  width: 50%;
}

</style>