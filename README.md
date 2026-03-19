# aspect-ratio-tool
A purely frontend aspect ratio visualizer and cropper

# ⬛ AspectMonolith

**AspectMonolith** 是一款轻量、极简且功能强大的**纯前端画幅可视化与图像裁切工具**。
专为设计师、视频剪辑师、社交媒体创作者（自媒体）和开发者打造，帮助你告别对“数字比例”的模糊认知，实现所见即所得的专业级排版与裁切。

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Build](https://img.shields.io/badge/build-passing-brightgreen.svg)
![Zero Dependencies](https://img.shields.io/badge/dependencies-0-success.svg)

---

## ✨ 核心特性 (Features)

* 📐 **动态比例可视化 (Dynamic Ratio Visualizer)**：无论输入常用比例还是自定义小数（如 2.35:1），画框都会实时平滑缩放，直观展示真实画幅。
* 🧮 **双向分辨率计算 (Resolution Calculator)**：一端输入宽度，自动算出高度。自带 **1080P / 2K / 4K** 快捷键，一键匹配最高清分辨率。
* 📱 **全平台社交预设 (Social Media Presets)**：内置 TikTok / IG Reels、YouTube、Instagram (Post & Portrait)、小红书等官方推荐比例及分辨率，一键切换至最佳发布规格。
* 🖼️ **沉浸式图像排版 (Immersive Image Cropper)**：
  * **纯本地处理**：图片直接在浏览器内存中读取，**绝不上传服务器，零延迟且 100% 保护隐私**。
  * **丝滑操控**：支持鼠标**拖拽平移**与**滚轮无极缩放**，搭配半透明暗黑遮罩，精准预览裁切区域。
* 📏 **专业构图辅助线 (Composition Guides)**：内置 **三分线 (Rule of Thirds)、黄金比例 (Golden Grid)、对角线 (Diagonals)**。采用智能阴影渲染黑科技，无论背景多亮或多暗，辅助线永远清晰可见。
* 📥 **所见即所得的精准导出 (Pixel-Perfect Export)**：调整好画面后，点击 Export，纯前端 Canvas 将在后台瞬间渲染并下载指定分辨率的无损高清 PNG 切图。
* 🌗 **双重主题 (Dark/Light Mode)**：内置精心调优的极客暗黑模式与明亮模式，一键切换，完美适配你的工作流偏好。

---

## 🚀 快速开始 (Getting Started)

因为这是一个**零依赖 (Zero-dependency)** 的纯前端项目，你完全不需要配置 Node.js、Webpack 或任何复杂的环境。

### 方法一：直接在线使用 (推荐)
直接访问本项目的 GitHub Pages 链接即可在线使用（完全免费且无需登录）：
👉 **[点击这里访问 AspectMonolith 在线版](https://你的用户名.github.io/你的仓库名/)** *(注：请在部署后替换此链接)*

### 方法二：本地运行
1. 克隆或下载本仓库到你的电脑：
   ```bash
   git clone [https://github.com/你的用户名/你的仓库名.git](https://github.com/你的用户名/你的仓库名.git)

找到 index.html 文件。

双击使用任何现代浏览器（Chrome, Edge, Safari, Firefox）打开它。

尽情享受！
