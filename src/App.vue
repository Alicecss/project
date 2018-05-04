<template>
  <div id="app">
    <!--头部导航栏-->
    <Header></Header>
    <!--广告轮播图-->
    <LoopPic></LoopPic>
  </div>
</template>

<script>
import Header from './components/Header'
import LoopPic from './components/LoopPic'
export default {
  name: 'App',
  components: {
    Header,
    LoopPic
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  margin:0;
  padding: 0;
}
</style>
