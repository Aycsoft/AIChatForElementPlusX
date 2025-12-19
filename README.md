
<div align="center">
<h2>💖项目模版，已经推出💖</h2>
<img src="https://cdn.element-plus-x.com/chat/1.webp" />&emsp;
<img src="https://cdn.element-plus-x.com/demo.webp" calss="element-plus-x-bubble" />&emsp;
<img src="https://cdn.element-plus-x.com/demo1.webp" calss="element-plus-x-bubble" />&emsp;
<img src="https://cdn.element-plus-x.com/demo3.webp" calss="element-plus-x-bubble" />&emsp;
<img src="https://cdn.element-plus-x.com/demo4.webp" calss="element-plus-x-bubble" />&emsp;
</div>

<div align="center">

[English](./README.en.md) | **简体中文**

</div>&emsp;

# 🚀 Element-Plus-X

**开箱即用的企业级 AI 组件库（基于 Vue 3 + Element-Plus）**

## 📦 安装

```bash
# NPM
npm install vue-element-plus-x

# PNPM（推荐）
pnpm install vue-element-plus-x

# Yarn
yarn install vue-element-plus-x

```

## 📚 使用案例

1. **按需引入**

```vue
<script>
import { BubbleList, Sender } from 'vue-element-plus-x';

const list = [
  {
    content: 'Hello, Element Plus X',
    role: 'user'
  }
];
</script>

<template>
  <div
    style="display: flex; flex-direction: column; height: 230px; justify-content: space-between;"
  >
    <BubbleList :list="list" />
    <Sender />
  </div>
</template>
```

2. **全局引入**

```ts
// main.ts
import { createApp } from 'vue';
import ElementPlusX from 'vue-element-plus-x';
import App from './App.vue';

const app = createApp(App);
// 使用 app.use() 全局引入
app.use(ElementPlusX);
app.mount('#app');
```

3. **CDN 引入**

```html
<!-- 该方法 有待测试 -->
<!-- CDN 引入 -->
<script src="https://unpkg.com/vue-element-plus-x@1.3.0/dist/umd/index.js"></script>
```
