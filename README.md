# 杂志架 · Magazine Rack

macOS 桌面杂志架：导入自己的图片，自动生成杂志封面并以两排书店陈列架展示。

[下载 Apple Silicon 安装包](https://github.com/just-talk-tomorrow/magazine-rack/releases/latest)

## 功能

- 日式、美式、构成主义、留白、印刷、拼贴等 240 种封面模板。
- 两排四本，每页最多八张；底部圆点切换真实图片页。
- 自然木框、Rams 等六种独立架体设计，封面带纸张、厚度和书本阴影。
- 顶部控件切换架体、封面风格、导入图片和随机换版。
- 点击书本预览，右键导出封面或移除；图片仅保存在本机。

## 安装

适用于 Apple Silicon（M 系列）和 macOS 14+。解压 ZIP 后把“杂志架.app”拖入“应用程序”。应用使用个人临时签名，未经过 Apple 公证。

## 从源码构建

```bash
bash scripts/build.sh
```

需要 Xcode 命令行工具。生成的视觉素材位于 `Resources/EditorialAssets`。

## 许可

本仓库公开源码，但未另行授予本项目源码或生成视觉素材的开源许可证；第三方组件继续遵循各自许可证。
