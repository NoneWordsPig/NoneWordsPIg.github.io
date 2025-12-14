---
permalink: /
title: "NoneWordsPig's private space"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# 文件
# 程序
# 网站
[百度](http://m.baidu.com)

[起点中文](https://chuangshi.qq.com/)
[qq音乐](https://y.qq.com)
[qq小说](https://book.qq.com/)

[聪明山](http://116.62.179.232)

style="border: none;">
<template id="external-content">
  <style>
    :host { display: block; border: 1px solid #ddd; }
  </style>
  <iframe src="https://chat.deepseek.com" width="600"  height="600"></iframe>
</template>

<script>
  customElements.define('external-page', class extends HTMLElement {
    connectedCallback() {
      const template = document.getElementById('external-content');
      this.attachShadow({mode: 'open'}).appendChild(template.content.cloneNode(true));
    }
  });
</script>
