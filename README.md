<div align="center">

<img src=".github/assets/whatsup-logo.png" width="128" height="128" alt="What's Up"/>

# What's Up

### Mac 菜单栏里的开发服务器管家

**看清后台正在跑什么，找出占用端口的服务，把不需要的进程一键收走。**

[官网](https://findwhatsup.com) · [立即购买 ¥18](https://findwhatsup.com/#pricing) · [下载最新版](https://github.com/HMyaoyuan/whatsup-releases/releases/latest/download/WhatsUp.dmg)

[![Download](https://img.shields.io/badge/下载_最新版-WhatsUp.dmg_·_3.55MB-0A84FF?style=for-the-badge&logo=apple)](https://github.com/HMyaoyuan/whatsup-releases/releases/latest/download/WhatsUp.dmg)
[![macOS](https://img.shields.io/badge/macOS-13_Ventura+-lightgrey?style=for-the-badge&logo=apple)](https://findwhatsup.com)
[![Apple Silicon](https://img.shields.io/badge/Apple_Silicon-M1_·_M2_·_M3_·_M4_·_M5-orange?style=for-the-badge)](https://findwhatsup.com)
[![Notarized](https://img.shields.io/badge/Apple-Developer_ID_Notarized-success?style=for-the-badge)](https://findwhatsup.com)

</div>

---

## 为什么需要 What's Up

写代码时，Mac 后台经常比你想象中更热闹。

一个 Cursor 窗口、一段 Claude Code 或 Kimi Code 会话、一个 Terminal、一个 Docker、一个前端 dev server，可能顺手就留下好几个 `node`、`python`、`vite`、`next dev`、`webpack`、`ollama`。窗口关了，服务却还在；项目切走了，端口还被占着；等你再次启动时，只剩一句熟悉的报错：

`address already in use`

What's Up 做的事情很简单：**把这些后台开发服务从黑盒里拿出来，放到菜单栏里给你看。**

## 你会得到什么

### 一眼看见正在运行的项目

What's Up 会把本机正在运行的开发进程整理成清晰列表。你不用打开活动监视器，也不用在终端里猜哪个 PID 属于哪个项目。

### 本地端口更好管理

哪个服务占着 `3000`、`5173`、`8080`，哪个项目还在监听本地端口，打开菜单栏就能看到。遇到端口冲突时，也能更早发现、更快处理。

### 多余进程更容易清理

不需要的服务可以直接从菜单栏收走。每天来回切换项目、分支、AI agent、Docker 和各种 dev server 的开发者，会明显少掉很多重复排查。

### 认出常见 AI 工具

Cursor、Claude Code、Kimi Code、Windsurf、Trae、Zed、Void 等 AI 编辑器和 coding agent 启动的服务，会尽量标出来源。你看到的不只是“有个进程在跑”，而是“它大概是谁起的”。

### 安静、轻量、装上就忘

What's Up 常驻菜单栏，不弹窗、不打扰。它不想成为另一个复杂 dashboard，只在你需要知道“后台到底跑了什么”时出现。

## 正式发布

What's Up 现在正式开放下载与购买。

它不是一个复杂的监控平台，也不是又一个需要配置半天的开发工具。它只是安静地待在菜单栏里，帮你回答一个每天都会遇到的问题：

**这台 Mac 后台到底还跑着什么？**

当你需要它时，点开菜单栏就能看到本地开发服务的状态；当你不需要它时，它就安静待着，不打扰你的工作流。

## 下载与安装

推荐下载：

**[WhatsUp.dmg](https://github.com/HMyaoyuan/whatsup-releases/releases/latest/download/WhatsUp.dmg)**

安装步骤：

1. 下载并打开 `WhatsUp.dmg`
2. 把 **What's Up** 拖入 **Applications**
3. 第一次打开时，如 macOS 提示安全确认，请到「系统设置 → 隐私与安全」点击「仍要打开」

这是独立开发者应用在 macOS 上的标准流程。

## 价格

- **3 天免费试用**：完整功能开放，不需要注册，不需要邮箱
- **¥18 / $3 一次买断**：绑定一台 Mac，终身有效
- **后续更新免费**
- 购买后不提供退款。请先充分试用，确认适合你的工作流后再下单。

购买授权：[findwhatsup.com/#pricing](https://findwhatsup.com/#pricing)

购买后领取 License Key：[findwhatsup.com/redeem](https://findwhatsup.com/redeem)

## 隐私

What's Up 的扫描在本机完成。它不上传你的项目路径、命令行参数、进程列表或端口列表。

许可证激活只会发送必要的 License Key 与设备绑定信息，用于确认购买状态。

## 系统要求

- macOS 13 Ventura 或以上
- Apple Silicon：M1 / M2 / M3 / M4 / M5
- Apple Developer ID 签名、公证、装订

## 关于这个发布仓

这个仓库只托管 **签名并公证过的 DMG 安装包** 和对外发布说明。GitHub 页面自动生成的 `Source code (zip/tar.gz)` 只是这个发布仓本身的快照，不是 What's Up 应用源码。

What's Up 的产品源码不在这个公开仓库中分发。

---

<div align="center">

**Made in Shenzhen · by [@HMyaoyuan](https://github.com/HMyaoyuan)**

<sub>Copyright © 2026 HMyaoyuan · Binaries distributed from this repository are governed by the EULA shipped with each release · Redistribution requires written permission.</sub>

</div>
