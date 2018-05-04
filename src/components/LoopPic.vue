<template>
  <!--广告栏 -> 轮播图-->
  <div class="banner">
    <div class="banner-pic">
      <ul>
        <li><img src="../common/image/bg1.jpg" alt=""></li>
        <li><img src="../common/image/bg2.jpg" alt=""></li>
        <li><img src="../common/image/bg3.jpg" alt=""></li>
      </ul>
    </div>
    <div class="carousel">
      <ol>
        <li>1</li>
        <li>2</li>
        <li>3</li>
      </ol>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
  .banner{
    position: relative;
    z-index: 1;
    display: block;
    height: 400px;
    width: 100%;
    overflow: hidden;
    float: left;
  }
  .banner img{
    height: 400px;
    width:80%;
    margin: 0 auto;
  }
</style>
