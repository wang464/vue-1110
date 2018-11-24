<template>
  <div class="row">
    <div class="col-xl">
      <div class="card text-center" v-if="week===6">
        <div class="card-body">
          <h5 class="card-title">周六</h5>
          <p>你好啊</p>
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
