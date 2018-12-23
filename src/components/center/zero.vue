<template>
  <div class="row">
    <div class="col-xl">
      <div class="card text-center">
        <div class="card-body">
          <h5 class="card-title">周日</h5>
          <a class="btn btn-light" target="_blank" href="http://www.zzzfun.com/vod-play-id-18-sid-1-nid-33.html">海贼王</a>
          <a class="btn btn-light" target="_blank" href="https://www.halihali.tv/v/haizeiwang/">海贼王2</a>
          <a class="btn btn-light" target="_blank" href="https://space.bilibili.com/927587/#/">木鱼说</a>
          <a class="btn btn-light" target="_blank" href="https://laod.cn/">老D博客</a>
          <a class="btn btn-light" target="_blank" href="https://learn.freecodecamp.one/">代码训练营中国</a>
          <a class="btn btn-light" target="_blank" href="http://web.jobbole.com/">伯乐在线</a>
          <a class="btn btn-light" target="_blank" href="http://www.zzzfun.com/vod-play-id-1194-sid-1-nid-8.html">哥布林杀手</a>
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
