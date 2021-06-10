<template>
<!--  <img alt="Vue logo" src="./assets/logo.png">-->
  <Landing/>
</template>

<script>
import Landing from './components/Landing.vue'

export default {
  name: 'App',
  components: {
    Landing
  }
}
</script>

<style>
@font-face {
  font-family: "Quatrocento Sans";
  font-style: normal;
  font-weight: 200;
  font-display: swap;
  src: url("/src/assets/fonts/QuattrocentoSans-Regular.ttf");
}
#app {
  font-family: "Quatrocento Sans", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  /*margin-top: 60px;*/
}
</style>
