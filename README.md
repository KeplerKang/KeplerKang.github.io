# Kepler Kang - 个人博客网站

这是一个基于HTML5、CSS3、JavaScript和GSAP的个人博客网站，用于展示Kepler Kang的作品集、个人简介和联系方式。

## 项目结构

```
designer-portfolio/
├── home.html          # 首页
├── works.html         # 作品列表页
├── about.html         # 关于我页面
├── contact.html       # 联系方式页面
├── works/             # 作品详情页
│   ├── work1.html
│   ├── work2.html
│   ├── work3.html
│   ├── work4.html
│   ├── work5.html
│   └── work6.html
└── README.md          # 项目说明
```

## 技术栈

- HTML5
- CSS3 (Tailwind CSS)
- JavaScript (ES6+)
- GSAP 动画库
- Font Awesome 图标库

## 功能特点

- 响应式设计，适配桌面端、平板和移动端
- 作品展示与分类筛选
- 平滑过渡动画效果
- 图片懒加载优化
- 联系表单交互
- 社交媒体链接

## 如何使用

1. 克隆或下载项目到本地
2. 使用现代浏览器（Chrome、Firefox、Safari、Edge等）直接打开HTML文件
3. 无需安装任何依赖，所有外部资源通过CDN加载

## 自定义内容

### 修改个人信息

1. 打开 `home.html`、`about.html` 和 `contact.html` 文件
2. 修改个人名称、职业、联系方式等信息
3. 替换个人照片（在 `about.html` 中）

### 添加/修改作品

1. 作品列表页：编辑 `works.html` 文件，添加/修改作品项
2. 作品详情页：在 `works` 目录下添加/修改HTML文件，确保链接正确

### 更改样式

1. 修改 Tailwind 配置（在各HTML文件的 `<script>` 标签中）
2. 调整自定义CSS（在各HTML文件的 `<style>` 标签中）

### 替换图片

1. 替换背景图和作品图片，保持相同的尺寸比例以确保最佳显示效果
2. 使用 picsum.photos 提供的图片服务，或替换为自己的图片链接

## 部署

1. 将所有文件上传到网站服务器
2. 确保文件结构保持不变
3. 访问主页（通常是 `home.html` 或 `index.html`）

## 浏览器兼容性

- Chrome (最新版)
- Firefox (最新版)
- Safari (最新版)
- Edge (最新版)

## 许可证

MIT
