<template>
  <div id="app">
    <!-- 路由出口 -->
    <router-view />
    <h1>黑马头条</h1>
    <div>
      <i class="toutiao toutiao-yanzhengma"></i>
      <van-button type="primary">主要按钮</van-button>
      <van-cell title="单元格" value="内容" size="large" />
<van-cell title="单元格" value="内容" size="large" label="描述信息" />
    </div>
  </div>
</template>
<script>
export default {
  name: 'App'
}
</script>

<style lang="less">
</style>
