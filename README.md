# Visual Web Components

一个展示现代 HTML 标签和 Web 组件的交互式演示项目。通过简洁的界面展示各种视觉化 HTML 标签的使用方法和效果。

## 🌟 特性

- **纯 HTML 标签展示** - 展示原生和现代 Web 组件的使用
- **交互式代码示例** - 可切换显示/隐藏代码块
- **响应式设计** - 支持桌面和移动设备
- **现代化 UI** - 使用 Tailwind CSS 构建的清洁界面
- **实时预览** - 所有组件都可以实时查看效果

## 📦 包含的组件

### 原生 HTML 标签
- **`<img>`** - 图片展示
- **`<video>`** - 视频播放
- **`<svg>`** - 矢量图形

### 现代 Web 组件
- **`<lottie-player>`** - Lottie 动画播放器
- **`<spine-viewer>`** - Spine 骨骼动画查看器
- **`<live2d-viewer>`** - Live2D 模型查看器
- **`<model-viewer>`** - 3D 模型查看器
- **`<a-frame>`** - WebVR/AR 场景
- **`<css-doodle>`** - CSS 艺术生成器
- **`<shader-toy>`** - WebGL 着色器演示

## 🚀 快速开始

### 安装依赖

```bash
npm install
```

### 启动开发服务器

```bash
npm run dev
```

### 构建生产版本

```bash
npm run build
```

### 预览构建结果

```bash
npm run preview
```

## 🛠️ 技术栈

- **构建工具**: Vite (Rolldown)
- **样式框架**: Tailwind CSS
- **3D 渲染**: Three.js
- **动画库**: 
  - Lottie Player
  - Spine Runtime
  - Live2D Cubism
- **WebGL**: Kokomi.js
- **WebVR/AR**: A-Frame
- **CSS 艺术**: CSS Doodle

## 📁 项目结构

```
visual-web-components/
├── index.html          # 主页面
├── package.json        # 项目配置
├── vite.config.ts      # Vite 配置
├── public/             # 静态资源
│   ├── kanade.jpg      # 示例图片
│   ├── 3rd_anv_title_03.mp4  # 示例视频
│   ├── Bonsai.glb      # 3D 模型文件
│   ├── kanade/         # Spine 动画资源
│   └── kanade-live2d/  # Live2D 模型资源
└── dist/               # 构建输出目录
```

## 🎮 使用方法

1. **浏览组件**: 页面展示了各种 HTML 标签和 Web 组件的实际效果
2. **查看代码**: 点击页面顶部的 "Toggle Code" 开关来显示/隐藏代码示例
3. **交互体验**: 部分组件支持交互，如点击 CSS Doodle 可以重新生成图案
4. **学习参考**: 每个组件都提供了基本的使用代码示例

## 🔗 相关链接

- [Lottie Player](https://github.com/LottieFiles/lottie-player)
- [Spine Viewer](https://github.com/alphardex/spine-viewer)
- [Live2D Viewer](https://github.com/alphardex/live2d-viewer)
- [Model Viewer](https://modelviewer.dev/)
- [A-Frame](https://aframe.io/)
- [CSS Doodle](https://css-doodle.com/)
- [Kokomi.js](https://kokomi-docs.netlify.app/)

## 📄 许可证

本项目仅用于学习和演示目的。

## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来改进这个项目！

---

**注意**: 本项目展示的是各种 Web 组件的基本用法，实际使用时请参考各组件的官方文档获取更详细的配置选项。