<template>
  <div>
    <el-menu class="el-menu-demo" mode="horizontal" background-color="green" text-color="#fff" active-text-color="#ffd04b">
      <el-menu-item index="1">
        <nuxt-link to="/" class="link-without-line">Home</nuxt-link>
      </el-menu-item>
      <el-menu-item index="2">
        <nuxt-link to="/post/list" class="link-without-line">Posts</nuxt-link>
      </el-menu-item>
      <el-menu-item index="3">
        <nuxt-link to="/post/new" class="link-without-line">Add Post</nuxt-link>
      </el-menu-item>
      <el-menu-item index="4">
        <nuxt-link to="/about" class="link-without-line">About</nuxt-link>
      </el-menu-item>
    </el-menu>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style>
</style>
