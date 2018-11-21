<template>
  <div id="app">
    <div class="container">
      <div class="row">
        <aside class="col-xl-3">
          <blog></blog>
          <sucha></sucha>
        </aside>
        <asideCenter></asideCenter>
        <aside class="col-xl-3">
          <yule></yule>
          <zaxiang></zaxiang>
        </aside>
      </div>
    </div>
  </div>
</template>

<script>
import asideCenter from "./components/asideCenter";
import blog from "./components/blog";
import zaxiang from "./components/zaxiang";
import yule from "./components/yule";
import sucha from "./components/sucha";

export default {
  name: "app",
  components: {
    asideCenter,
    blog,
    zaxiang,
    yule,
    sucha
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
