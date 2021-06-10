<template>
  <b-container fluid id="footer" class="section footer-section">
    <b-container fluid class="footer-grid">
      <b-container class="upper-left-cell">
        <b-link class="anchor-link hvr-hang mb-3" to="/">Blog</b-link>
      </b-container>
      <b-container class="upper-right-cell">
        <b-link class="anchor-link hvr-hang mb-3" to="/">Art</b-link>
      </b-container>
      <b-container class="middle-cell">
        <b-link class="anchor-link hvr-hang mb-3" to="/">Contact</b-link>
      </b-container>
      <b-container class="lower-left-cell">
        <b-link class="anchor-link hvr-hang mb-3" to="/">Services</b-link>
      </b-container>
      <b-container class="lower-right-cell">
        <b-link class="anchor-link hvr-hang mb-3" to="/">Support</b-link>
      </b-container>
            <b-container class="copyright-left-cell mb-5 mb-md-0">
        <span>Copyright Froconic Design <b-icon-dash-circle font-scale=".5"></b-icon-dash-circle> 2021</span>
      </b-container>
      <b-container class="copyright-right-cell mb-5 mb-md-0">
        <span>Handcrafted By <b-link href="https://akiraallen.com/">Froconic Design</b-link></span>
      </b-container>
      <b-container class="arrow-cell">
        <b-link href="#hero">
          <b-icon-arrow-up class="anchor-arrow" font-scale="5"></b-icon-arrow-up>
        </b-link>
      </b-container>
    </b-container>
  </b-container>

</template>

<script>
  export default {

  }
</script>

<style>
  /* .section.footer-section {
    height: 40vh;
  } */

  .footer-grid {
    display: grid;
    align-items: center;
    grid-row: auto;
  }



  @media screen and (min-width: 40rem) {
    .footer-grid {
      display: grid;
      align-items: center;
      grid-template-areas:
        "upper-left . upper-right "
        ". middle  ."
        "lower-left . lower-right"
        "copyright-left arrow-cell copyright-right";
    }

    .footer-container {
      position: relative;
      height: 100%;
      font-size: 2rem;
    }

    .upper-left-cell {
      grid-area: upper-left;
      grid-row: 1 / 1;
      grid-column: 1 / 3;
    }

    .upper-right-cell {
      grid-area: upper-right;
      grid-row: 1 / 3;
      grid-column: 2 / 4;
    }

    .middle-cell {
      grid-area: middle;
      grid-row: 2 / 4;
      grid-column: 1 / 4;
    }

    .lower-left-cell {
      grid-area: lower-left;
      grid-row: 4 / 6;
      grid-column: 1 / 3;

    }

    .lower-right-cell {
      grid-area: lower-right;
      grid-row: 4 / 6;
      grid-column: 2 / 4;
    }

    .copyright-left-cell {
      grid-area: copyright-left;
      grid-row: 6 / 6;
      grid-column: 1 / 2;
    }

    .copyright-right-cell {
      grid-area: copyright-right;
      grid-row: 6 / 6;
      grid-column: 3 / 4;

    }

    .arrow-cell {
      grid-area: arrow-cell;
      grid-row: 6 / 6;
      grid-column: 1 / 4;
    }

  }
</style>