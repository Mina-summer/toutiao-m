<template>
  <div id="app">
    <router-view></router-view>
    <div class="box">

    </div>
    <div>
      <i class="iconfont icon-shoucang"></i>
      <van-tabs v-model="active">
        <van-tab title="标签 1">内容 1</van-tab>
        <van-tab title="标签 2">内容 2</van-tab>
        <van-tab title="标签 3">内容 3</van-tab>
        <van-tab title="标签 4">内容 4</van-tab>
      </van-tabs>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang='less'>
.box{
  width: 200px;
  height: 60px;
  background-color: pink;
}
</style>
