<script setup lang="ts">

</script>

<template>
  <div class="container mx-auto px-4 py-8">
    <div class="text-center">
      <h1 class="text-4xl font-bold text-gray-800 mb-4">欢迎来到首页</h1>
      <p class="text-lg text-gray-600 mb-8">这是一个使用 Vue 3 + TypeScript + Tailwind CSS 构建的简单首页</p>
      
      <div class="bg-white rounded-lg shadow-md p-6 max-w-md mx-auto">
        <h2 class="text-2xl font-semibold text-gray-700 mb-4">功能特性</h2>
        <ul class="text-left space-y-2">
          <li class="flex items-center">
            <span class="w-2 h-2 bg-blue-500 rounded-full mr-3"></span>
            Vue 3 Composition API
          </li>
          <li class="flex items-center">
            <span class="w-2 h-2 bg-green-500 rounded-full mr-3"></span>
            TypeScript 支持
          </li>
          <li class="flex items-center">
            <span class="w-2 h-2 bg-purple-500 rounded-full mr-3"></span>
            Tailwind CSS 样式
          </li>
          <li class="flex items-center">
            <span class="w-2 h-2 bg-orange-500 rounded-full mr-3"></span>
            Vue Router 路由
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>