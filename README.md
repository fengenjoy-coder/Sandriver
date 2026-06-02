# MBC Sandriver

MBC Sandriver 项目展示网站。

## 在线访问

🔗 [https://fengenjoy-coder.github.io/Sandriver](https://fengenjoy-coder.github.io/Sandriver)

## 项目简介

本项目将 MBC Sandriver 的设计资料整理为一个长滚动式单页网站，便于在线浏览和分享。

网站包含 30 页从 Figma 导出的 SVG 幻灯片，采用深绿色主题，自适应屏幕宽度。

## 文件结构

```
.
├── index.html          # 主页面（长滚动布局）
├── style.css           # 样式文件
├── svg/                # SVG 幻灯片（1.svg - 30.svg）
│   ├── 1.svg
│   ├── 2.svg
│   └── ...
└── fonts/              # StyreneA 字体文件
    ├── StyreneA-Medium.otf
    └── StyreneA-Regular.otf
```

## 技术说明

- 纯静态 HTML/CSS，无需构建工具
- 响应式设计，适配桌面和移动设备
- SVG 文件较大，首次加载可能需要一些时间
