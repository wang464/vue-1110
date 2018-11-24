<template>
  <div class="row">
    <div class="col-xl">
      <div class="card text-center" v-if="week===5">
        <div class="card-body">
          <h5 class="card-title">周五</h5>
          <a class="btn btn-light" target="_blank" href="http://www.ruanyifeng.com/blog/">阮一峰日志</a>
          <a class="btn btn-light" target="_blank" href="https://weixin.sogou.com/weixin?type=1&s_from=input&query=%E5%8D%B0%E8%B1%A1%E7%AC%94%E8%AE%B0&ie=utf8&_sug_=n&_sug_type_=">印象笔记一周收藏排行</a>
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
