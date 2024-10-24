---
title: Git 基础
description: 每个 Vue 应用都需要通过实例化 Vue 来实现
date: 2024-09-03T22:16:31+08:00
slug: git100001
categories:
    - Git
---

每个 Vue 应用都需要通过实例化 Vue 来实现。

语法格式如下：

```js
var vm = new Vue({
  // 选项
})
```

接下来让我们通过实例来看下 Vue 构造器中需要哪些内容：

```html
<div id="vue_det">
    <h1>site : {{site}}</h1>
    <h1>url : {{url}}</h1>
    <h1>{{details()}}</h1>
</div>
<script type="text/javascript">
    var vm = new Vue({
        el: '#vue_det',
        data: {
            site: "菜鸟教程",
            url: "www.runoob.com",
            alexa: "10000"
        },
        methods: {
            details: function() {
                return  this.site + " - 学的不仅是技术，更是梦想！";
            }
        }
    })
</script>
```