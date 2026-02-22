# 部署指南

## 快速开始

### 1. 创建GitHub仓库

1. 登录 [GitHub](https://github.com)
2. 创建新仓库，命名为：`dige-precision-nutrition`（或你喜欢的名字）
3. 将本文件夹内容上传到仓库

### 2. 启用GitHub Pages

1. 进入仓库设置（Settings）
2. 找到 **Pages** 左侧菜单
3. Source 选择 **Deploy from a branch**
4. Branch 选择 **main**，文件夹选择 **/(root)**
5. 点击 Save

### 3. 等待部署

约1-2分钟后，网站将上线：`https://你的用户名.github.io/仓库名/`

### 4. 自定义域名（可选）

在 Pages 设置中添加自定义域名：

```
dige.com
```

或使用免费的 `.github.io` 域名。

---

## 本地预览

如果想在本地预览：

```bash
# 安装Ruby和Jekyll
# Mac: brew install ruby
# Ubuntu: apt install ruby

# 安装依赖
gem install jekyll jekyll-sitemap

# 本地预览
jekyll serve

# 访问 http://localhost:4000
```

---

## 添加新文章

在 `_posts` 文件夹中添加新文章：

```
文件命名格式：YYYY-MM-DD-文章标题.md
```

文章模板：

```markdown
---
layout: default
title: 你的文章标题
date: 2026-01-15
categories: [分类1, 分类2]
tags: [标签1, 标签2]
---

# 文章标题

正文内容...
```

---

## SEO优化

已在 `_config.yml` 中配置：

- Meta描述
- Open Graph标签
- 结构化数据（可选添加JSON-LD）

---

## 常见问题

### Q: 文章显示404？
A: 确保文件名格式正确：`2026-01-01-title.md`

### Q: 图片不显示？
A: 将图片放入 `assets/images/`，引用路径：`/assets/images/图片名.jpg`

### Q: 想修改样式？
A: 编辑 `assets/css/style.css`

---

*有问题请联系：*
*抖音：JK171513*
