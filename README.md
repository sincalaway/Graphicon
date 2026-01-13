# 🎨 Graphic Code Pro (智能设计 - 吸附增强版)

> 一个基于浏览器、单文件运行的轻量级矢量图形设计工具。无需安装，即开即用。

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Fabric.js](https://img.shields.io/badge/Powered%20by-Fabric.js-red)](http://fabricjs.com/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

**如果你觉得这个项目有趣或对你有帮助，请给它一个 ⭐️ Star！你的支持是我更新的动力！**

---

## ✨ 项目简介 (Introduction)

**Graphic Code Pro** 是一个纯前端实现的在线平面设计工具。它集成了专业的矢量编辑功能，拥有极简的暗色模式 UI，核心逻辑基于强大的 Fabric.js 库，并经过深度定制优化。

这个版本特别增强了 **智能吸附 (Smart Snap)** 和 **辅助线系统**，让设计排版如同在专业桌面软件中一样丝滑。

## 🚀 核心功能 (Features)

* **📐 智能辅助与吸附 (Smart Guides & Snapping)**
    * 支持对象中心、边缘自动吸附。
    * 自动显示对齐辅助线（画布中心对齐 + 对象间对齐）。
    * 吸附阈值平滑，操作手感极佳。

* **🎨 智能色彩管理**
    * **图片取色**：上传图片自动提取主色调，支持一键替换图片特定颜色（基于像素距离算法）。
    * **矢量换色**：自动识别 SVG/矢量图形中的所有颜色，支持批量替换。

* **history 历史记录系统**
    * 深度优化的撤销 (Undo) / 重做 (Redo) 机制。
    * 包含状态去重与防抖逻辑，避免无效操作污染历史栈。

* **🛠 丰富的工具箱**
    * 内置图标素材库（基础形状、医疗、餐饮、创意等分类）。
    * 图层管理（置顶、置底、成组/解组）。
    * 文字编辑（加粗、斜体、字号）。

* **💾 导出与保存**
    * 支持导出高清透明 PNG。
    * 支持导出可编辑 SVG 矢量源文件。

## 📦 如何使用 (Getting Started)

本项目是 **单文件 (Single-file)** 架构，极易部署和修改。

1.  **下载代码**：Clone 本仓库或直接下载 ZIP。
2.  **运行**：直接双击打开 `index.html` 文件即可在浏览器中运行（推荐 Chrome/Edge）。
    * *注意：由于图片跨域安全策略，涉及本地图片处理的高级功能建议在本地服务器环境（如 Live Server）下运行以获得最佳体验。*

## 🎮 快捷键 (Shortcuts)

| 按键 | 功能 |
| :--- | :--- |
| `Ctrl + Z` | 撤销 (Undo) |
| `Ctrl + Y` 或 `Ctrl + Shift + Z` | 重做 (Redo) |
| `Delete` / `Backspace` | 删除选中元素 |
| `Ctrl + C` | 复制当前元素 |
| `Ctrl + G` | 成组 (Group) |
| `Ctrl + Shift + G` | 解组 (Ungroup) |
| 拖拽元素 | 自动触发智能吸附 |

## 🛠️ 技术栈 (Tech Stack)

* **Core**: HTML5, CSS3, Vanilla JavaScript
* **Graphics Engine**: [Fabric.js v5.3.1](http://fabricjs.com/)
* **Icons**: FontAwesome 6.4.0
* **Fonts**: Google Fonts (Inter)

## 🤝 贡献 (Contributing)

非常欢迎提交 Issue 和 Pull Request！
如果你有更好的吸附算法优化、新的素材库数据或者 UI 改进建议，请随时提交。

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request

## 📄 开源协议 (License)

本项目基于 [MIT License](LICENSE) 开源。

---

**Don't forget to star ⭐️ the repo if you found this useful!**