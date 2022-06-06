<template>
  <el-menu class="el-menu-demo" mode="horizontal">
    <el-menu-item>
      <nuxt-link to="/dashboard"> Página inicial </nuxt-link>
    </el-menu-item>
    <el-menu-item>
      <nuxt-link to="/pessoal"> Página pessoal </nuxt-link>
    </el-menu-item>
    <div class="w-12 h-12 mt-[5px] ml-2 rounded-full bg-red-200 float-right"></div>
  </el-menu>
</template>

<style>
.el-menu-item:active {
  background: blue;
}
</style>

