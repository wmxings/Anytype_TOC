[中文](README.md) | [English](README/README_en-US.md) | [繁體中文](README/README_zh-TW.md) | [Русский](README/README_ru-RU.md) | [日本語](README/README_ja-JP.md) | [한국어](README/README_ko-KR.md) | [Deutsch](README/README_de-DE.md) | [Français](README/README_fr-FR.md)

# Anytype 悬浮目录

## 项目背景
自 2022 年起，Anytype 社区用户就一直在呼吁添加悬浮目录功能。遗憾的是，截至 2025 年 4 月，这个功能仍未在官方开发计划中。有趣的是，Notion 作为 Anytype 的主要竞品之一，在实现悬浮目录功能时积极性也不高。

## 解决方案
本项目通过自定义 CSS 的方式，为 Anytype 实现了一个简洁优雅的悬浮目录功能。这个解决方案与社区用户 [@sandroid](https://community.anytype.io/t/custom-table-of-contents-custom-css/27360/8) 的思路不谋而合。

在设计过程中，参考了少数派（[sspai.com](https://sspai.com)）网站的悬浮目录风格。受 Anytype 只支持自定义 CSS 而不支持 JS 的限制，虽无法实现 100% 的还原，但最终效果依然非常棒。


## 效果展示
![悬浮目录效果演示](image/IMG_20250411_234639.gif)


## 功能特点
- 简洁优雅的悬浮目录布局设计
- 目录跟随页面滚动，提供便捷导航
- 支持目录项悬停效果


## 使用方法
1. 打开 Anytype，依次点击 `文件 -> 打开 -> 自定义 CSS`
2. 将 `custom.css` 或 `custom.min.css` 的内容复制到 `自定义 CSS` 文件中
3. 重启 Anytype 即可生效


## 注意事项
- 如需自定义样式，可以修改 `custom.css` 中的相关参数
