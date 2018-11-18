<template>
    <section class="col-xl">
        <search></search>
        <commonly></commonly>
        <!-- 周二/周三 -->
        <div class="row">
          <div class="col-xl">
            <div class="card text-center" v-if="week===2">
              <div class="card-body">
              <h5 class="card-title">周二</h5>
                <a class="btn btn-light" target="_blank" href="http://www.zzzfun.com/vod-detail-id-1164.html">东京食尸鬼</a>
              </div>
            </div>
          </div>
        </div>
        <div class="row">        
          <div class="col-xl">
            <div class="card text-center" v-if="week===3">
              <div class="card-body">
              <h5 class="card-title">周三</h5>
              </div>
            </div>
          </div>
        </div>
        <!-- 周四/周五 -->
        <div class="row">
          <div class="col-xl">
            <div class="card text-center" v-if="week===4">
              <div class="card-body">
              <h5 class="card-title">周四</h5>
                <a class="btn btn-light" target="_blank" href="http://www.silisili.co/anime/1951.html">兔女郎学姐</a>
                <a class="btn btn-light" target="_blank" href="http://www.dilidili.wang/watch3/75158/">兔女郎学姐2</a>
              </div>
            </div>
          </div>
        </div>
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
        <!-- 周六/周日 -->
        <div class="row">
          <div class="col-xl">
            <div class="card text-center" v-if="week===6">
              <div class="card-body">
              <h5 class="card-title">周六</h5>
              </div>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-xl">
            <div class="card text-center" v-if="week===0">
              <div class="card-body">
              <h5 class="card-title">周日</h5>
                <a class="btn btn-light" target="_blank" href="http://www.zzzfun.com/vod-play-id-18-sid-1-nid-33.html">周日海贼王</a>
              </div>
            </div>
          </div>
        </div>
        <!-- 周一/每月 -->
        <div class="row">
          <div class="col-xl">
            <div class="card text-center" v-if="week===1">
              <div class="card-body">
              <h5 class="card-title">周一</h5>
              </div>
            </div>
          </div>          
        </div>
    </section>
</template>
<script>
import commonly from "./center/commonly";
import search from "./center/search";
export default {
  components: {
    commonly,
    search
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

