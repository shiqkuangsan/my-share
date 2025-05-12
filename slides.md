---
theme: apple-basic
background: https://source.unsplash.com/collection/94734566/1920x1080
# 幻灯片相关信息
title: 开发者 2.0 之与 AIDE 并肩作战
info: |
  ## AIDE 技术分享
  基于道家「道法术器场势」思想的 AIDE 开发理念与实践分享

  讲者：XXX
# 应用样式
class: text-center
# 绘图功能
drawings:
  persist: false
# 切换动画
transition: slide-left
# 启用 MDC 语法
mdc: true
---

# 乘风破浪, 开发者 2.0 之与 AIDE 并肩作战

基于道家「道法术器场势」思想的 AIDE 开发理念与实践分享

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  按空格键进入下一页 <carbon:arrow-right />
</div>

<div class="abs-br m-6 text-xl">
  <button @click="$slidev.nav.openInEditor()" title="在编辑器中打开" class="slidev-icon-btn">
    <carbon:edit />
  </button>
</div>

<!--
欢迎大家参加本次 AIDE 技术分享！
-->

--- 
src: ./pages/intro.md
---

---
src: ./pages/dao.md
---

---
src: ./pages/fa.md
---

---
src: ./pages/shu.md
---

---
src: ./pages/qi.md 
---

---
src: ./pages/chang.md
---

---
src: ./pages/shi.md
---

---
src: ./pages/summary.md
---

---
src: ./pages/imported-slides.md
---