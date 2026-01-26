# 广州市着相科技有限公司 - 企业官网

一个现代化、专业的企业官网项目，采用纯前端技术构建，可直接部署到 GitHub Pages。

## 项目介绍

本项目为广州市着相科技有限公司的企业官网，展示公司简介、核心业务、企业优势和联系方式等信息。网站采用响应式设计，兼容桌面端和移动端设备。

## 技术栈

- **HTML5** - 页面结构
- **CSS3** - 样式设计（包含 CSS 变量、Grid 布局、Flexbox、动画等现代特性）
- **JavaScript (ES6+)** - 交互功能（导航切换、滚动动画、返回顶部等）

## 项目结构

```
web/
├── index.html          # 主页面文件
├── css/
│   └── style.css       # 样式表
├── js/
│   └── main.js         # JavaScript 交互脚本
└── README.md           # 项目说明文档
```

## 功能特性

### 页面内容
- ✅ 响应式导航栏（固定顶部，移动端汉堡菜单）
- ✅ 首页横幅区域（Hero Section）
- ✅ 关于我们（公司简介、数据统计）
- ✅ 核心业务（6大业务模块展示）
- ✅ 企业优势（4大核心优势）
- ✅ 联系我们（地址、邮箱、工作时间）
- ✅ 页脚版权信息

### 交互功能
- 🎯 平滑滚动导航
- 🎯 移动端菜单切换
- 🎯 滚动淡入动画
- 🎯 返回顶部按钮（滚动后自动显示）
- 🎯 Hover 悬停效果
- 🎯 导航栏滚动阴影变化

### 设计特点
- 🎨 现代商务风格配色（深蓝 + 白色）
- 🎨 清晰的视觉层次
- 🎨 流畅的动画效果
- 🎨 响应式布局（适配手机、平板、桌面）

## 快速开始

### 本地预览

1. 克隆或下载项目到本地
2. 直接在浏览器中打开 `index.html` 文件即可预览

或使用简单的 HTTP 服务器：

```bash
# 使用 Python 3
python -m http.server 8000

# 使用 Python 2
python -m SimpleHTTPServer 8000

# 使用 Node.js (需安装 http-server)
npx http-server -p 8000
```

然后在浏览器访问 `http://localhost:8000`

### 部署到 GitHub Pages

#### 方法一：通过 GitHub 网页端

1. 在 GitHub 创建新仓库（例如：`company-website`）
2. 将项目文件上传到仓库
3. 进入仓库的 Settings → Pages
4. Source 选择 `main` 分支，文件夹选择 `/ (root)`
5. 点击 Save，等待几分钟后访问生成的 URL

#### 方法二：通过命令行

```bash
# 初始化 Git 仓库
git init

# 添加所有文件
git add .

# 提交
git commit -m "Initial commit: Add company website"

# 关联远程仓库（替换为你的仓库地址）
git remote add origin https://github.com/你的用户名/你的仓库名.git

# 推送到 GitHub
git branch -M main
git push -u origin main
```

然后在 GitHub 仓库中开启 Pages 功能（参考方法一步骤 3-5）。

## 自定义修改

### 修改公司信息

在 `index.html` 中查找并修改以下内容：

- 公司名称：搜索 "广州市着相科技有限公司"
- 联系邮箱：搜索 "helper@hellome.fun"
- 公司地址：在 "联系我们" 区块中修改
- 其他文本内容：直接在对应的 HTML 标签中修改

### 修改配色方案

在 `css/style.css` 的 CSS 变量中修改：

```css
:root {
    --primary-color: #1e3a8a;      /* 主色调 */
    --secondary-color: #3b82f6;    /* 次要色调 */
    --dark-color: #1e293b;         /* 深色 */
    --light-color: #f8fafc;        /* 浅色背景 */
    --gray-color: #64748b;         /* 灰色文字 */
}
```

### 添加或删除业务模块

在 `index.html` 中找到 `<div class="services-grid">` 部分，复制或删除 `<div class="service-card">` 整个区块即可。

## 浏览器兼容性

- ✅ Chrome (最新版)
- ✅ Firefox (最新版)
- ✅ Safari (最新版)
- ✅ Edge (最新版)
- ✅ 移动端浏览器

## 性能优化

- 无外部依赖，加载速度快
- CSS 和 JS 文件均已优化
- 使用 CSS3 动画，性能流畅
- 图片使用 SVG 图标，体积小

## 注意事项

1. 本项目不包含后端功能，所有内容为静态展示
2. 如需添加表单提交功能，建议使用第三方服务（如 Formspree、Netlify Forms 等）
3. 建议添加真实的公司 Logo 和业务图片以提升视觉效果
4. 可根据实际需求添加网站统计代码（如 Google Analytics）

## License

MIT License - 可自由使用和修改

## 联系方式

如有问题或建议，请联系：helper@hellome.fun

---

**广州市着相科技有限公司** © 2026
