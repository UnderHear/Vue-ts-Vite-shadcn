# Vue TypeScript 基础框架

这是一个基于 Vue 3 + TypeScript + Vite + shadcn-vue组件库 的现代化前端开发框架模板。

## 技术栈

- **Vue 3** `^3.5.18` - 渐进式 JavaScript 框架
- **TypeScript** `^5.9.2` - JavaScript 的超集，提供静态类型检查
- **Vite** `^7.1.2` - 下一代前端构建工具
- **Vue Router** `^4.5.1` - Vue.js 官方路由管理器
- **Tailwind CSS** `^4.1.12` - 实用优先的 CSS 框架
- **Reka UI** `^2.4.1` - 基于 Radix UI 和 Tailwind CSS 的组件库
- **Lucide Vue Next** `^0.542.0` - 美观的图标库
- **Class Variance Authority** `^0.7.1` - 类变体管理工具
- **Tailwind Merge** `^3.3.1` - Tailwind CSS 类名合并工具
- **clsx** `^2.1.1` - 条件类名构建工具

## 项目结构

```
src/
├── components/          # 可复用组件
│   └── ui/             # shadcn/ui 组件
├── views/              # 页面组件
│   └── Index.vue       # 首页
├── router/             # 路由配置
│   └── index.ts        # 路由定义
├── lib/                # 工具库
│   └── utils.ts        # 工具函数
├── assets/             # 静态资源
├── App.vue             # 根组件
├── main.ts             # 应用入口
└── style.css           # 全局样式
```

##  开发

### 安装依赖

```bash
npm install
```

### 启动开发服务器

```bash
npm run dev
```

### 构建生产版本

```bash
npm run build
```

### 预览生产构建

```bash
npm run preview
```

## 特性

-  **快速开发** - Vite 提供极速的热重载体验
-  **类型安全** - TypeScript 提供完整的类型检查
-  **现代 UI** - shadcn/ui 组件库提供美观的界面组件
-  **响应式设计** - Tailwind CSS 实现完美的移动端适配
-  **路由管理** - Vue Router 提供单页应用路由功能
-  **开箱即用** - 预配置的开发环境，快速启动项目

##  使用说明

这是一个基础框架模板，你可以在此基础上：

1. 添加新的页面组件到 `src/views/` 目录
2. 在 `src/router/index.ts` 中配置新的路由
3. 使用 shadcn-vue 组件构建界面
4. 在 `src/components/` 中创建可复用组件
5. 根据需要安装额外的依赖包

## 添加 shadcn-vue 组件

### 安装组件

使用以下命令添加 shadcn-vue 组件到你的项目：

添加 Button 组件
```bash
npx shadcn-vue@latest add button
```
添加其他组件
```bash
npx shadcn-vue@latest add accordion
npx shadcn-vue@latest add alert
npx shadcn-vue@latest add card
```

想要添加更多的组件，请查看 [shadcn-vue 组件官网](https://www.shadcn-vue.com/docs/components/accordion.html) 获取完整的组件列表和使用文档。

### 使用组件

添加组件后，你可以在项目中这样使用：

```vue
<script setup lang="ts">
import { Button } from '@/components/ui/button'
</script>

<template>
  <div>
    <Button>Click me</Button>
  </div>
</template>
```

## 贡献

欢迎提交 Issue 和 Pull Request 来改进这个模板！
