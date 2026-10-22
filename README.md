# hello1573.github.io

Mengxi LI（hello1573）的个人项目主页。

网站地址：<https://hello1573.github.io/>

使用原生 HTML、CSS 与 SVG 制作，无需构建工具或第三方前端依赖，适配桌面和手机，并支持键盘导航与减少动画的系统设置。

## 内容维护

- `index.html`：个人介绍、项目卡片及 GitHub 链接。
- `styles.css`：颜色、版式与响应式布局。
- `favicon.svg`：网站图标。
- `.nojekyll`：让 GitHub Pages 直接发布静态文件。

当前展示的项目为 [Search-for-papers](https://github.com/hello1573/Search-for-papers) 和 [shanji](https://github.com/hello1573/shanji)，简介依据其公开 README 整理。装饰性等高线为手绘 SVG，并非实际分析结果。

## 本地预览

在本目录运行：

```sh
python -m http.server 8765 --bind 127.0.0.1
```

然后访问 <http://127.0.0.1:8765/>。

## 发布

GitHub 仓库 Settings → Pages：

- Source：Deploy from a branch
- Branch：`main`
- Folder：`/(root)`

更新文件并推送到 `main` 后，GitHub Pages 会重新部署。

GitHub Pages 仅托管静态页面。已有 Flask 后端可继续在阿里云运行；以后可在 `index.html` 添加其真实网址的入口。本次未配置或修改阿里云服务。
