<template>
  <div id="app">
    <div class="container">
    <div class="row">
      <asideRight></asideRight>
      <asideCenter></asideCenter>
      <asideLeft></asideLeft>
    </div>
    </div>
  </div>
</template>

<script>
import asideRight from "./components/asideRight";
import asideLeft from "./components/asideLeft";
import asideCenter from "./components/asideCenter";
export default {
  name: "app",
  components: {
    asideLeft,
    asideCenter,
    asideRight
  }
};
</script>

<style>
/* #app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
