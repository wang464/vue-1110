<template>
  <div class="row">
    <div class="col-xl">
      <div class="card text-center" v-if="week===0">
        <div class="card-body">
          <h5 class="card-title">周日</h5>
          <a class="btn btn-light" target="_blank" href="http://www.zzzfun.com/vod-play-id-18-sid-1-nid-33.html">海贼王</a>
          <a class="btn btn-light" target="_blank" href="https://space.bilibili.com/927587/#/">木鱼说</a>
          <a class="btn btn-light" target="_blank" href="https://laod.cn/">老D博客</a>

        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
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
</style>
