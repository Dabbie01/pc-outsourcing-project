<!--
 * @Author: Dabbie 2310734576@qq.com
 * @Date: 2022-05-08 09:23:18
 * @LastEditors: Dabbie 2310734576@qq.com
 * @LastEditTime: 2023-02-20 15:48:16
 * @FilePath: \vue-xhc-master\src\components\navMenu\navmenu.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<template>
  <div>
     <el-menu theme="dark" :default-active="activeIndex" class="el-menu-demo" mode="horizontal" unique-opened="true">
          <el-submenu index="1" class="nav-item">
            <template slot="title">标题三</template>
            <el-menu-item index="1-1">选项1</el-menu-item>
            <el-menu-item index="1-2">选项2</el-menu-item>
            <el-menu-item index="1-3">选项3</el-menu-item>
          </el-submenu>
          <el-submenu index="2" class="nav-item">
            <template slot="title">业务平台</template>
            <el-menu-item index="2-1"><router-link to="/business">商务主页</router-link></el-menu-item>
            <el-menu-item index="2-2"><router-link to="/developing">发展主页</router-link></el-menu-item>
          </el-submenu>
          <el-submenu index="3" class="nav-item">
            <template slot="title">标题一</template>
            <el-menu-item index="3-1">选项1</el-menu-item>
            <el-menu-item index="3-2">选项2</el-menu-item>
            <el-menu-item index="3-3">选项3</el-menu-item>
          </el-submenu>
     </el-menu>
  </div>
</template>

<script>

  export default {
    data () {
      return {
        activeIndex: '1'
      }
    }
  }
</script>

<style>
 .nav-item{
   float: right!important;
 }
 
</style>
