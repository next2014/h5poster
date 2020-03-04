<!-- <template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template> -->
<template>
  <div id="main">
    <router-view/>
  </div>
</template>


<script>
// import HelloWorld from './components/HelloWorld.vue'
// export default {
//   name: 'App',
//   components: {
//     HelloWorld
//   }
// }
</script>

<style>
@import "assets/css/reset.css";
html, body {
  width: 100%;
  height: 100%;
  background-color: #222222;
}
#main {
  width: 100%;
  height: 100%;
  position: relative;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
