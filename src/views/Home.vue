<template>
  <div class="home">
    home
    急啊卡电话卡就是
  </div>
</template>

<script>
  export default {
    name: 'home',
    created() {
      this.axios.get('./mock/home.json').then((response) => {
        console.log(response);
      })
    }
  }
</script>

<style>
  @import "../assets/reset.css";
</style>
