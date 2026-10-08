# 博磊的个人说明书

一份生活手账风格的个人说明书网页，用纸张质感、胶带贴纸、便签卡片的方式介绍自己。

## 在线预览

部署后访问：`https://<你的用户名>.github.io/<仓库名>/`

## 本地预览

直接用浏览器打开 `index.html` 即可。

## 部署到 GitHub Pages

1. 在 GitHub 新建仓库（如 `personal-manual`）
2. 将本目录所有文件推送到仓库：
   ```bash
   git init
   git add .
   git commit -m "个人说明书"
   git branch -M main
   git remote add origin https://github.com/<用户名>/<仓库名>.git
   git push -u origin main
   ```
3. 仓库 Settings → Pages → Source 选择 `main` 分支、根目录 `/(root)` → Save
4. 等待一分钟即可访问

## 目录结构

```
├── index.html          # 主页面（GitHub Pages 入口）
├── 博磊的个人说明书.html  # 同内容文件
├── assets/
│   ├── hero-desk.jpg   # 封面手账图
│   ├── life-scenes.jpg # 生活场景图
│   └── avatar.jpg      # 头像
└── README.md
```

## 技术栈

- 纯 HTML + CSS + 原生 JavaScript
- 手绘水彩插画
- 响应式适配（手机/平板/桌面）
- 无任何构建依赖
