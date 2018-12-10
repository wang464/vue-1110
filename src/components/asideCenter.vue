<template>
  <section class="col-xl">
    <search></search>
    <commonly></commonly>
    <!-- 0-6 -->
    <tools></tools>
    <two></two>
    <four></four>
    <five></five>
    <zero></zero>
    <one></one>
    <there></there>
    <six></six>
  </section>
</template>
<script>
import two from './center/two';
import there from './center/there';
import four from './center/four';
import five from './center/five';
import zero from './center/zero';
import six from './center/six';
import one from './center/one';
import tools from "./center/tools";
import commonly from "./center/commonly";
import search from "./center/search";
export default {
  components: {
    commonly,
    search,
    tools,
    one,
    six,
    zero,
    five,
    four,
    there,
    two
  },
  data: function() {
    return {
      week: 6
    };
  },
  mounted: function() {
    let d = new Date();
    this.week = d.getDay();
  }
};
</script>

<style>
/* section * {
  border: 1px solid #c3c3c3;
} */
</style>

