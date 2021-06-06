<template>
  <div v-b-toggle.open-menu id="app">
    <router-view />
  </div>
</template>


<style>
  @font-face {
    font-family: "Odin Round";
    src: url('https://github.com/Froconic/app/blob/feature%2Fhome/src/assets/fonts/odin-rounded.regular.otf')
  }

  @font-face {
    font-family: "Typo Round";
    src: url('https://github.com/Froconic/app/blob/feature%2Fhome/src/assets/fonts/typo-round.bold-demo.otf')
  }

  body {
    font-size: 16px;
    color: #F4F5F6;
    background-color: #2388ff;
    font-family: 'Work Sans', sans-serif;
  }

  a {
    color: #F4F5F6;
  }

  a:hover {
    color: #EBF4FF;
    text-decoration: none;
  }

  #app {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #F4F5F6;
    cursor: default;
    width: 100vw;
    margin: 0;
    overflow-x: none;
  }

  #nav a.router-link-exact-active {
    color: #EBF4FF;
  }

    .grid {
    display: grid;
    grid-auto-flow: row;
    grid-gap: 2em;
    margin: 5rem auto;
    width: 100%;
    justify-content: center;
    align-content: center;
  }

  @media screen and (min-width:768px) {
    .grid {
      grid-template-columns: repeat(3, 33%);
      grid-auto-flow: column;
    }
  }


</style>