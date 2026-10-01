# 亲本组图 · Nepenthes Hybrid Cards

杂交猪笼草亲本组图生成页（Claude Design 导出，静态页面，GitHub Pages 托管）。

- 线上地址：https://yabbie.github.io/nepenthes-hybrid-cards/
- 数据（卡片、照片）仅保存在访问者浏览器的 localStorage / IndexedDB，不上传服务器。

## 更新方式

从 Claude Design 重新导出后：

1. 将 `亲本组图 vN.dc.html` 复制为本目录的 `index.html`；
2. 用导出的 `support.js` 覆盖本目录的 `support.js`；
3. 页面引用的 `assets/` 素材一并更新；
4. `git add -A && git commit && git push`。

## 运行时外部依赖

React / ReactDOM（unpkg）、Google Fonts、导出图片时的 `html-to-image`（jsDelivr）。
