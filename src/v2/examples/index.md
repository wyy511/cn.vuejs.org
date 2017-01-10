---
title: Markdown 编辑器
type: examples
order: 0
---

> 蠢萌的 Markdown 编辑器。

<iframe width="100%" height="500" src="https://jsfiddle.net/chrisvfritz/rdjjpc7a/embedded/result,html,js,css" allowfullscreen="allowfullscreen" frameborder="0"></iframe>




js代码更改后：
new Vue({
  el: '#editor',
  data: {
    input: '# hello',
    compiledMarkdown:''
  },
  methods: {
    update: function (e) {
      this.input = e.target.value
      this.compiledMarkdown = this.input
    }
  }
})
