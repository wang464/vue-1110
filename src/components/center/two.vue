<template>
  <div class="row">
    <div class="col-xl">
      <div class="card text-center">
        <div class="card-body">
          <h5 class="card-title">周二</h5>
          <a class="btn btn-light" target="_blank" href="http://www.zzzfun.com/vod-detail-id-1164.html">东京食尸鬼</a>
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
