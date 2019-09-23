<style lang="scss">
  .nav-bar-title {
    color: #00bb2c;
  }

  .main-content {
    padding-bottom: 112px;
  }
</style>

<template>
  <div id="app">
    <van-nav-bar fixed>
      <template slot="title">
        <span class="nav-bar-title">曹操彩选</span>
      </template>
    </van-nav-bar>
    <div class="main-content">
      <router-view></router-view>
    </div>
    <van-tabbar v-model="active" active-color="#00bb2c">
      <van-tabbar-item icon="home-o">分类</van-tabbar-item>
      <van-tabbar-item icon="cart-o">购物车</van-tabbar-item>
      <van-tabbar-item icon="friends-o">我的订单</van-tabbar-item>
    </van-tabbar>
  </div>
</template>
