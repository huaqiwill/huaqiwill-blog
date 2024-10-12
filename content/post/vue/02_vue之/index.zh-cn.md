---
title: Vue.js 模板语法
description: 这里简单介绍PHP图像处理
date: 2024-09-03T22:16:31+08:00
slug: vue100002
categories:
    - Vue
---

Vue.js 使用了基于 HTML 的模板语法，允许开发者声明式地将 DOM 绑定至底层 Vue 实例的数据。

Vue.js 的核心是一个允许你采用简洁的模板语法来声明式的将数据渲染进 DOM 的系统。

结合响应系统，在应用状态改变时， Vue 能够智能地计算出重新渲染组件的最小代价并应用到 DOM 操作上。

```html
<div id="app">
  <p>{{ message }}</p>
</div>
```