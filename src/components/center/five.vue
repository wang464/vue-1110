<template>
  <div class="row">
    <div class="col-xl">
      <div class="card text-center" v-if="week===5">
        <div class="card-body">
          <h5 class="card-title">周五</h5>
          <a class="btn btn-light" target="_blank" href="http://www.ruanyifeng.com/blog/">阮一峰日志</a>
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
