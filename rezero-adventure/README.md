# 🌟 命运之门 · 异世界冒险

> 从零开始的异世界冒险任务管理工具

一个灵感来自《Re:从零开始的异世界生活》的PWA应用，帮助你以RPG游戏的方式管理现实生活中的目标与任务。

## ✨ 功能特性

- **三种任务类型**：主线任务、支线任务、突发任务
- **任务管理系统**：创建、编辑、删除任务，设置奖励与成就
- **任务日记**：为每个任务记录冒险感想与心得
- **能量系统**：完成任务获得梦想之力、智慧之力、生命源力
- **角色面板**：查看冒险者资料、能量积累、成就图鉴
- **庆祝动画**：完成任务时触发华丽的星星粒子特效
- **成就系统**：10个隐藏成就等待解锁
- **离线可用**：PWA技术支持，无网络也能使用
- **手机桌面**：可添加到手机主屏幕，像原生App一样使用

## 📱 安装到手机

### iPhone (Safari)
1. 用 Safari 打开部署后的网页链接
2. 点击底部分享按钮
3. 选择「添加到主屏幕」
4. 桌面上会出现App图标

### Android (Chrome)
1. 用 Chrome 打开部署后的网页链接
2. 点击右上角菜单（⋮）
3. 选择「添加到主屏幕」或「安装应用」
4. 桌面上会出现App图标

## 🚀 部署到 GitHub Pages

1. **Fork 或创建新仓库**
   - 在 GitHub 创建一个新仓库，命名为 `rezero-adventure`（或你喜欢的名字）

2. **上传文件**
   - 将本项目所有文件上传到仓库根目录
   - 确保 `index.html` 在根目录

3. **开启 GitHub Pages**
   - 进入仓库 Settings → Pages
   - Source 选择「Deploy from a branch」
   - Branch 选择「main」→「/ (root)」
   - 点击 Save

4. **访问你的应用**
   - 等待几分钟后，访问 `https://你的用户名.github.io/rezero-adventure/`

## 🎨 自定义图标

项目中的 `icons/` 文件夹包含各尺寸的占位图标。建议替换为：
- 发光的魔法书
- 中世纪命运之门
- 魔法月亮

你可以使用 [Favicon.io](https://favicon.io/) 或 [AppIcon Generator](https://appicon.co/) 生成所需尺寸。

## 🛠 技术栈

- 纯 HTML5 + CSS3 + Vanilla JavaScript
- PWA (Progressive Web App)
- LocalStorage 本地数据持久化
- SVG 矢量角色绘制
- CSS 动画与 Canvas-free 粒子效果

## 📄 文件结构

```
rezero-adventure/
├── index.html          # 主应用页面
├── manifest.json       # PWA 配置
├── sw.js              # Service Worker
├── icons/             # 应用图标（多尺寸）
│   ├── icon-72x72.png
│   ├── icon-96x96.png
│   ├── icon-128x128.png
│   ├── icon-144x144.png
│   ├── icon-152x152.png
│   ├── icon-192x192.png
│   ├── icon-384x384.png
│   └── icon-512x512.png
└── README.md
```

## 💾 数据说明

所有数据存储在浏览器本地（LocalStorage），包括：
- 任务列表与日记
- 角色能量与成就
- 冒险者手记

**注意**：清除浏览器数据会导致存档丢失。建议定期导出重要记录。

## 🌙 设计理念

> 「即使从零开始，也要开辟通往未来的道路。」

这个工具试图将枯燥的任务管理转化为充满仪式感的冒险体验。每一次完成任务，都是一次小小的升级；每一篇日记，都是冒险者手记中的一页。

---

*Made with ✦ magic*
