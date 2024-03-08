<!-- 使用 type="home" 属性设置首页，其他页面不需要设置，默认为page；推荐使用json5，更强大，且允许注释 -->
<route lang="json5" type="home">
{
  style: {
    navigationStyle: 'custom',
    navigationBarTitleText: '首页',
  },
}
</route>
<template>
  <view>
    <tar-bar class="top-bar"><h4 class="tb_solt">畅聊</h4></tar-bar>
  </view>
</template>

<script lang="ts" setup>
import TarBar from '@/components/tar-bar/tar-bar.vue'
// 获取屏幕边界到安全区域距离
// const { safeAreaInsets } = uni.getSystemInfoSync()

// const description = ref()

onLoad(() => {})
</script>

<style>
.main-title-color {
  color: #d14328;
}
</style>
