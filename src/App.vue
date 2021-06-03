<template>
  <div v-b-toggle.open-menu id="app">
    <router-view/>
  </div>
</template>


<style>
  body {
  background-color:#2388FF;
}

  a {
    color: #F4F5F6;
  }

  a:hover {
    color: #EBF4FF;
    text-decoration: none;
  }

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
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

.home {
  /* width: 100%; */
}
</style>
