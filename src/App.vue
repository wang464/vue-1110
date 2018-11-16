<template>
  <div id="app">
    <div class="container">
    <div class="row">
      <aside class="col-xl-3">
        <sucha></sucha>
        <jishu></jishu>
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
import jishu from "./components/jishu";
import zaxiang from "./components/zaxiang";
import yule from "./components/yule";
import sucha from "./components/sucha";


export default {
  name: "app",
  components: {
    asideCenter,
    jishu,
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
