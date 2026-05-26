# 我的博客

使用 Jekyll + GitHub Pages 搭建的中文博客。

## 功能

- 响应式设计，移动端友好
- 暗色 / 亮色主题切换
- 文章分页
- 按年份归档
- 标签 & 分类
- RSS 订阅
- SEO 优化

## 快速开始

### 1. 创建 GitHub 仓库

- 仓库名 `用户名.github.io` → 访问 `https://用户名.github.io`
- 其他仓库名 → 访问 `https://用户名.github.io/仓库名/`（需在 `_config.yml` 设置 `baseurl: /仓库名`）

### 2. 推送代码

```bash
git init
git add .
git commit -m "初始化博客"
git remote add origin https://github.com/用户名/仓库名.git
git push -u origin main
```

### 3. 启用 GitHub Pages

进入仓库 → Settings → Pages → Source 选择 `main` 分支 → Save

几分钟后即可访问你的博客。

### 4. 本地预览（可选）

```bash
gem install bundler
bundle install
bundle exec jekyll serve
```

访问 `http://localhost:4000`

## 写文章

在 `_posts/` 下新建文件，命名格式 `YYYY-MM-DD-标题.md`：

```markdown
---
layout: post
title: "文章标题"
date: 2026-05-26
tags: [标签1, 标签2]
---

正文内容，支持 Markdown。
```

## 自定义

- 修改 `_config.yml` → 站点标题、描述、作者、社交链接
- 替换 `assets/images/avatar.jpg` → 头像
- 修改 `_layouts/default.html` 中的 CSS 变量 → 颜色主题

## 目录结构

```
├── _config.yml          # 站点配置
├── _layouts/
│   ├── default.html     # 主布局（含样式）
│   ├── post.html        # 文章布局
│   └── page.html        # 页面布局
├── _posts/              # 博客文章
├── assets/images/       # 图片资源
├── index.html           # 首页
├── about.md             # 关于页面
├── archives.md          # 归档页面
└── feed.xml             # RSS
```

## License

MIT
