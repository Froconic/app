<template>
  <b-container fluid id="footer" class="section anchor-section">
    <b-container fluid class="anchor-grid">
      <b-container class="upper-left">
        <b-link class="anchor-link hvr-hang mb-3" to="/">Services</b-link>
      </b-container>
      <b-container class="upper-right">
        <b-link class="anchor-link hvr-hang mb-3" to="/">Art</b-link>
      </b-container>
      <b-container class="middle">
        <b-link class="anchor-link hvr-hang mb-3" to="/">Blog</b-link>
      </b-container>
      <b-container class="lower-left">
        <b-link class="anchor-link hvr-hang mb-3" to="/">Resource Well</b-link>
      </b-container>
      <b-container class="lower-right">
        <b-link class="anchor-link hvr-hang mb-3" to="/">About</b-link>
      </b-container>
      <b-container class="arrow">
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
  @media screen and (min-width:768) {
    .anchor-link {
      font-size: 2rem;
    }
  }

  .anchor-link {
    color: #000a14;
    width: 50%;
    padding: 1rem;
    display: inline-block;
    vertical-align: middle;
    -webkit-transform: perspective(1px) translateZ(0);
    transform: perspective(1px) translateZ(0);
    box-shadow: 0 0 1px rgba(0, 0, 0, 0);
    -webkit-transition-duration: 0.3s;
    transition-duration: 0.3s;
    -webkit-transition-property: transform;
    transition-property: transform;
    font-size: 1rem;
    width: 100%;
  }

  .anchor-link:hover,
  .anchor-link:focus,
  .anchor-link:active {
    color: #F4F5F6;
    border: 3px solid #F4F5F6;
    border-radius: 5px;
    -webkit-transform: scale(1.1);
    transform: scale(1.1);
    box-shadow: inset 0 0 0 3px #F4F5F6, 0 0 1px rgba(0, 0, 0, 0);
  }

  @-webkit-keyframes hvr-hang {
    0% {
      -webkit-transform: translateY(8px);
      transform: translateY(8px);
    }

    50% {
      -webkit-transform: translateY(4px);
      transform: translateY(4px);
    }

    100% {
      -webkit-transform: translateY(8px);
      transform: translateY(8px);
    }
  }

  @keyframes hvr-hang {
    0% {
      -webkit-transform: translateY(8px);
      transform: translateY(8px);
    }

    50% {
      -webkit-transform: translateY(4px);
      transform: translateY(4px);
    }

    100% {
      -webkit-transform: translateY(8px);
      transform: translateY(8px);
    }
  }

  @-webkit-keyframes hvr-hang-sink {
    100% {
      -webkit-transform: translateY(8px);
      transform: translateY(8px);
    }
  }

  @keyframes hvr-hang-sink {
    100% {
      -webkit-transform: translateY(8px);
      transform: translateY(8px);
    }
  }

  .hvr-hang {
    -webkit-transform: perspective(1px) translateZ(0);
    transform: perspective(1px) translateZ(0);
  }

  .hvr-hang:hover,
  .hvr-hang:focus,
  .hvr-hang:active {
    -webkit-animation-name: hvr-hang-sink, hvr-hang;
    animation-name: hvr-hang-sink, hvr-hang;
    -webkit-animation-duration: .3s, 1.5s;
    animation-duration: .3s, 1.5s;
    -webkit-animation-delay: 0s, .3s;
    animation-delay: 0s, .3s;
    -webkit-animation-timing-function: ease-out, ease-in-out;
    animation-timing-function: ease-out, ease-in-out;
    -webkit-animation-iteration-count: 1, infinite;
    animation-iteration-count: 1, infinite;
    -webkit-animation-fill-mode: forwards;
    animation-fill-mode: forwards;
    -webkit-animation-direction: normal, alternate;
    animation-direction: normal, alternate;
  }

  .anchor-grid {
    display: flex;
    flex-direction: column;
  }



  @media screen and (min-width: 768px) {
    .anchor-grid {
      display: grid;
      align-items: center;
      grid-template-areas:
        "upper-left . upper-right "
        ". middle  ."
        "lower-left . lower-right"
        "arrow arrow arrow";
    }

    .anchor-section {
      height: 100vh;
    }

    .upper-left {
      grid-area: upper-left;
      grid-row: 1 / 1;
      grid-column: 1 / 3;
    }

    .upper-right {
      grid-area: upper-right;
      grid-row: 1 / 1;
      grid-column: 2 / 4;
    }

    .middle {
      grid-area: middle;
      grid-row: 2 / 4;
      grid-column: 1 / 4;
    }

    .lower-left {
      grid-area: lower-left;
      grid-row: 4 / 6;
      grid-column: 1 / 3;

    }

    .lower-right {
      grid-area: lower-right;
      grid-row: 4 / 6;
      grid-column: 2 / 4;
    }


    }

    .arrow {
      grid-area: arrow;
      grid-row: 6 / 6;
      grid-column: 1 / 4;
    }

</style>