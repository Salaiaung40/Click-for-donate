<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style>
* {
  margin: 0px;
  padding: 0px;
  border: 0px;
  outline: 0px;
  box-sizing: border-box;
  font-size: 100%;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
  /* background-color: rgba(187, 179, 159, 0.925); */
  background: rgba(187, 179, 159, 0.925);
  width: 100vw;
  height: 100vh;
}
</style>
