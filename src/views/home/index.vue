<template>
  <!-- 放置一个外层容器 -->
  <el-container>
    <!-- 左右布局 -->
    <el-aside style="background-color:#353b4e;min-height:100vh;width:230px">
      <!-- 放置左侧组件 -->
      <layout-aside></layout-aside>
    </el-aside>
    <!-- 再放一个container -->
    <el-container>
      <!-- 上下布局 -->
      <el-header>
        <layout-header></layout-header>
      </el-header>
      <el-main style="padding:0">
        <!-- 二级路由容器 -->
        <router-view></router-view>
      </el-main>
    </el-container>
  </el-container>
</template>

<script>
// import layoutAside from '../../components/home/layout-aside' // 引入
// import layoutHeader from '../../components/home/layout-header' // 引入
export default {
  // 'layout-aside': layoutAside,
  // 'layout-header': layoutHeader
}
</script>

<style>

</style>
