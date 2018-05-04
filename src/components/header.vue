<template>
  <!--顶部导航栏-->
  <div class="header">
    <!--图标猫眼电影-->
    <div class="header-inner">
      <a href="" class="logo"></a>
    </div>
    <!--城市定位-->
    <div class="city-container">
      <div class="city-selected">
        <div class="city-name">
          广州
        </div>
      </div>
    </div>
    <!--导航栏菜单-->
    <div class="nav">
      <ul class="navbar">
        <li>首页</li>
        <li>电影</li>
        <li>影院</li>
        <li>榜单</li>
        <li>热点</li>
      </ul>
    </div>
    <!--APP下载-->
    <div class="app-download">
      <img src="../common/image/phone.png" class="iphone-icon">
      <span>APP下载</span>
      <span class="caret"></span>
    </div>
    <!--搜索框-->
    <from class="search-click">
      <input type="search" class="search" placeholder="找影视剧、娱乐、综艺">
      <input type="submit" class="submit" value>
    </from>
    <!--登录-->
    <div class="user-info">
      <div class="person-pic">
        <img src="../common/image/person.png" alt="">
        <span class="caret"></span>
        <!--<ul class="user-menu">-->
        <!--<li>-->
        <!--<a href="">登录</a>-->
        <!--<a href="">注册</a>-->
        <!--<a href="">退出</a>-->
        <!--</li>-->
        <!--</ul>-->
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
  div{
    display: block;
  }
  .header{
    position: fixed;
    top: 0;
    z-index:999;
    width: 100%;
    min-width: 1200px;
    background-color: #fff;
    border-bottom:1px solid #d8d8d8;
  }
  li{
    list-style: none;
  }
  .header-inner{
    width: 1200px;
    margin: 0;
    height: 80px;
    padding: 0;
    float: left;
  }
  .header-inner .logo{
    float: left;
    width: 133px;
    height: 80px;
    background:url("../common/image/icon01.png") no-repeat 0;
    background-size:contain;
  }
  .city-container{
    position: absolute;
    float: left;
    height: 100%;
    left: 167px;
    top:-2px;
  }
  .city-container .city-selected {
    cursor: pointer;
    height: 100%;
    padding: 0 10px;
    border:1px solid transparent;
    border-width:0 1px;
    z-index: 101;
  }
  .city-container .city-name{
    display: inline-block;
    margin-top: 32px;
    color: #333;
  }
  .nav{
    display: inline-block;
    background-color:#fff;
    overflow: hidden;
    margin-left: 40px;
    float: left;
  }
  .nav .navbar li{
    margin: 18px 18px;
    border: none;
    float: left;

  }
  .app-download{
    float: left;
    margin-left: 25px;
    margin-top:14px;
    margin-right:15px;
  }
  .search-click{
    float: left;
    margin: 10px 10px;
  }
  .search{
    display: inline-block;
    height: 40px;
    line-height: 1.2;
    width: 200px;
    border: 1px solid #ccc;
    border-radius: 30px;
    background-color: #faf8fa;
    overflow: hidden;
    color: #333;
    font-size: 14px;
  }
  .submit{
    display: inline-block;
    position: absolute;
    height: 40px;
    width: 40px;
    background-color: red;
    border-radius: 30px;
    cursor: pointer;
    right: 188px;
    top:25px;
    background-image: url("../common/image/search.png");
  }
  .user-info{
    position: absolute;
    right: 115px;
    top: 25px;
  }
  .person-pic{
    display: block;
    margin: 0 10px;
    float: left;
  }
  .person-pic img {
    width: 40px;
    height: 40px;
  }
</style>
