<template>
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
