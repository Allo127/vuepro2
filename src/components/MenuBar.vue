<template>
  <van-tabbar v-model="active" route>
    <van-tabbar-item replace to="/" icon="wap-home-o">标签</van-tabbar-item>
    <van-tabbar-item replace to="/" icon="other-pay">标签</van-tabbar-item>
    <van-tabbar-item replace to="/" icon="shopping-cart-o">标签</van-tabbar-item>
    <van-tabbar-item replace to="/" icon="user-o">标签</van-tabbar-item>
  </van-tabbar>
</template>

<script>
  export default {
    data() {
      return {
        active: 0
      }
    }
  }
</script>

<style>
</style>
