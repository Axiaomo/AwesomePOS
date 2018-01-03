<template>
  <div id="app">
    <!-- 左侧导航 -->
    <left-nav></left-nav>
    <!-- 操作区域 -->
   <div class="main">
      <router-view/>
   </div>
  </div>
</template>

<script>
import leftNav from './components/common/leftNav'
export default {
  name: 'app',
  components:{
    leftNav
  }
}
</script>

<style>
.main{
  float: left;
  width: 95%;
  background-color: #EFF2F7;
  height: 100%;
  overflow: auto;
}
</style>
