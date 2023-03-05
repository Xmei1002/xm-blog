<template>
  <div class="nav">
    <div class="nav-logo">
      <span class="nav-logo-img"></span>
      <span class="nav-logo-span">Blog</span>
    </div>
    <div class="nav-menu">
      <ul class="nav-menu-ul">
        <li><el-icon><House /></el-icon><span>首页</span></li>
        <li><el-icon><Reading /></el-icon><span>文章</span></li>
        <li><el-icon><Guide /></el-icon><span>标签</span></li>
        <li><el-icon><Postcard /></el-icon><span>留言</span></li>
        <li><el-icon><User /></el-icon><span>关于</span></li>
        <li><el-icon><ChatLineRound /></el-icon><span>碎语</span></li>
        <li><el-icon><Search /></el-icon><span>搜索</span></li>
      </ul>
    </div>
  </div>
</template>

<script setup>

</script>

<style scoped>
  .nav{
    display: flex;
    justify-content: space-between;
    line-height: 60px;
    align-items: center;
  }
  .nav-logo{
    font-size: 30px;
    margin-left: 300px;
    color: white;
  }
  
  .nav-menu{
    margin-right: 200px;
  }
  .nav-menu-ul{
    display: flex;
    color: white;
  }
  .nav-menu-ul li{
    display: flex;
    align-items: center;
    font-size: 18px;
    padding: 10px;
  }
  .nav-menu-ul li:hover{
    background-color:rgba(22, 5, 16, 0.2);
    cursor: pointer;
  }
  .nav-menu-ul li span{
    margin-left: 6px;
  }
</style>