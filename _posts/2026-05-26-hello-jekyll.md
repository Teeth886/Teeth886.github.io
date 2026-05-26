---
layout: single
title: "开始使用 Jekyll 搭建博客"
date: 2026-05-26
author: Teeth
categories: [教程]
tags: [Jekyll, GitHub Pages, 博客]
---

这是你的第一篇博客文章！你可以用 Markdown 语法来写作。

## 快速开始

### 1. 本地预览

安装依赖后运行：

```bash
bundle install
bundle exec jekyll serve
```

然后访问 `http://localhost:4000` 即可预览。

### 2. 发布文章

在 `_posts/` 目录下创建新文件，文件名格式为：

```
YYYY-MM-DD-标题.md
```

文件开头需要包含 YAML 头信息：

```yaml
---
layout: single
title: "文章标题"
date: 2026-05-26
author: Teeth
tags: [标签1, 标签2]
---
```

### 3. Markdown 示例

**粗体**、*斜体*、`行内代码`

> 这是一段引用文字

| 功能 | 语法 |
|------|------|
| 链接 | `[文本](URL)` |
| 图片 | `![描述](图片URL)` |
| 代码块 | 用三个反引号包裹 |

### 4. 插入图片

将图片放在 `assets/images/` 目录下：

```markdown
![图片描述](/assets/images/example.jpg)
```

---

开始写作吧！删除或修改这篇示例文章，创建属于你自己的内容。
