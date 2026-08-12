---
title: Firestar — 一款清新美观的 Astro 博客主题
published: 2026-08-12
description: "Firestar 是一款基于 Astro 框架和 Fuwari 模板开发的现代化个人博客主题，专为技术爱好者和内容创作者设计。"
image: ./images/firefly1.avif
tags: [Firestar, Astro, 博客主题, 开源]
category: 项目介绍
pinned: true
---

## 什么是 Firestar？

**Firestar** 是一款基于 Astro 框架和 Fuwari 模板开发的清新美观且现代化个人博客主题，专为技术爱好者和内容创作者设计。

![Firestar 主题预览](./images/firefly1.avif)

该主题融合了现代 Web 技术栈，提供了丰富的功能模块和高度可定制的界面，让您能够轻松打造出专业且美观的个人博客网站。

## ✨ 核心特性

### 🚀 极致性能

基于 **Astro 7** 构建，采用静态站点生成（SSG）技术，页面加载速度极快。配合 **Svelte 5** 实现交互组件，兼顾静态页面的性能和动态交互体验。

### 🎨 精美设计

清新现代的 UI 设计，支持亮色/暗色主题自动切换，响应式布局完美适配桌面端和移动端。

![暗色模式展示](./images/firefly2.avif)

### 📝 强大的内容支持

- **Markdown / MDX** 双格式支持
- **Mermaid** 流程图渲染
- **PlantUML** 图表支持
- **KaTeX** 数学公式
- **Expressive Code** 增强代码块
- **GitHub 仓库卡片** 一键嵌入

### 🔍 内置搜索

集成 **Pagefind** 全文搜索，无需第三方服务，开箱即用。

### 💬 评论系统

支持多种评论系统：Twikoo（基于 MongoDB）、Giscus（基于 GitHub Discussions）、Waline（带评论管理后台）。

### 🖼️ 图片画廊

内置相册功能，支持瀑布流布局展示图片集。

![布局展示](./images/firefly3.avif)

## 🛠️ 技术栈

- **Astro 7** — 静态站点生成框架
- **Svelte 5** — 交互式 UI 组件
- **Swup.js** — 页面切换动画（SPA 体验）
- **Tailwind CSS** — 原子化 CSS 样式
- **Pagefind** — 静态全文搜索
- **Biome** — 代码格式化与检查

## 📦 快速开始

**环境要求：** Node.js >= 22，包管理器推荐 pnpm

```bash
# 克隆项目
git clone https://github.com/wind-001/Firefly.git
cd Firefly

# 安装依赖
pnpm install

# 启动开发服务器
pnpm dev
```

访问 `http://localhost:4321` 即可预览。

```bash
# 构建生产版本
pnpm build

# 预览构建结果
pnpm preview
```

构建产物在 `dist/` 目录，可部署到任何静态托管平台。

## 🚀 部署方式

Firestar 支持多种部署方式：

- **Cloudflare Pages** — 推荐，支持 GitHub 自动部署
- **Vercel** — 一键部署，配置简单
- **Netlify** — 静态托管首选
- **Cloudflare Workers** — 边缘计算部署

## ⚙️ 高度可配置

所有功能都通过 `src/config/` 目录下的 TypeScript 文件进行配置：

- `siteConfig.ts` — 站点基本信息、主题设置
- `sidebarConfig.ts` — 侧边栏布局
- `navBarConfig.ts` — 导航栏菜单
- `profileConfig.ts` — 作者信息
- `commentConfig.ts` — 评论系统配置
- `friendsConfig.ts` — 友链配置

无需修改代码，只需调整配置文件即可个性化你的博客。

## 📚 更多资源

- **在线预览**：[Firefly Demo](https://firefly.cuteleaf.cn/)
- **使用文档**：[Firefly 文档](https://docs-firefly.cuteleaf.cn/)
- **开源地址**：[CuteLeaf/Firefly](https://github.com/CuteLeaf/Firefly)

## 📄 开源协议

本项目基于 [MIT](https://github.com/CuteLeaf/Firefly/blob/master/LICENSE) 协议开源，您可以自由使用、修改和分发。

---

> **Firestar** — 让每一片叶子都能闪耀 ✨
