# 影之诗计血器 / Shadowverse Life Counter

一个给 **影之诗（Shadowverse）实卡对战** 用的网页计血器。单文件、零依赖、离线可用，手机浏览器直接打开就能用。

**在线使用：** https://mico-cpu.github.io/sv-life-counter/

## 特点

- **单文件**：全部 HTML/CSS/JS 内联，没有外部请求，断网也能跑
- **手机优先**：适配刘海屏（`safe-area-inset`）与触摸操作
- **深浅色**：跟随系统 `prefers-color-scheme` 自动切换
- **对局功能**：双方血量、骰子等对局中常用操作

## 本地打开

直接用浏览器打开 `index.html` 即可，不需要任何服务器。

## 部署

GitHub Pages，从 `main` 分支根目录发布。改动 `index.html` 后推上去，几十秒后线上生效。

## License

MIT
