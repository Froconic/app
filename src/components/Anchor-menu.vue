<template>
  <b-container fluid id="menu-section" class="section menu-section">
      <b-row align-v="baseline" align-content="between" cols-sm="2" class="mb-sm-5 anchor-row">
        <b-col cols=12 w-50 class="px-5 test">
          <a class="anchor-link hvr-hang mb-3" href="#services-section">Services</a>
        </b-col>
        <b-col cols-sm=8>
          <a class="anchor-link hvr-hang mb-3" href="#art-section">Art</a>
        </b-col>
      </b-row>
      <b-row align-v="baseline" align-h="center" class="mb-sm-5 anchor-row">
        <b-col>
          <a class="anchor-link hvr-hang mb-3" href="#blog-section">Blog</a>
        </b-col>
      </b-row>
      <b-row align-v="baseline" align-h="between" cols="1" cols-sm="2" class="mb-3 anchor-row">
        <b-col cols-sm=8>
          <a class="anchor-link hvr-hang mb-3" href="#resource-section">Resources</a>
        </b-col>
        <b-col cols-sm=8 class="mb-5">
          <a class="anchor-link hvr-hang mb-3" href="#about-section">About</a>
        </b-col>
      </b-row>
      <b-row align-v="baseline" align-h="center">
        <b-link href="#blog-section">
                <b-icon align-self="end" class="anchor-arrow mb-5" icon=arrow-down font-scale=5></b-icon>
              </b-link>
      </b-row>
    </b-container>
</template>

<script>
export default {

}
</script>

<style>

@media screen and (min-width:768){
  .anchor-link{
    font-size: 
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
}

.anchor-link:hover, .anchor-link:focus, .anchor-link:active {
  color: #F4F5F6;
  border: 3px solid #F4F5F6;
  border-radius: 5px;
  -webkit-transform: scale(1.1);
  transform: scale(1.1);
  box-shadow: inset 0 0 0 3px  #F4F5F6, 0 0 1px rgba(0, 0, 0, 0);
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
.hvr-hang:hover, .hvr-hang:focus, .hvr-hang:active {
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

</style>