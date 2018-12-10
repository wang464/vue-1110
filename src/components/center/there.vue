<template>
  <div class="row">
    <div class="col-xl">
      <div class="card text-center">
        <div class="card-body">
          <h5 class="card-title">周三</h5>
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
