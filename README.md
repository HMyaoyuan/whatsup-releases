<div align="center">

<img src=".github/assets/whatsup-logo.png" width="128" height="128" alt="What'sUp"/>

# What'sUp

**A macOS menu-bar inventory of every background process your dev work — and your AI — has spun up.**

[findwhatsup.com](https://findwhatsup.com) · [Buy · ¥18 / $3](https://findwhatsup.com/#pricing) · [Releases](https://github.com/HMyaoyuan/whatsup-releases/releases)

</div>

---

## 中文

### 这是什么？

你自己跑的 `npm run dev`、`docker compose up`、`python manage.py runserver`，加上 Cursor / Claude Code / Codex 顺手帮你起的那些——大多数时候你并不记得到底开了哪些。

**What'sUp** 常驻 macOS 菜单栏，按 Git 仓库把当下所有后台进程全列出来，标出重复的、忘关的，给你一键收走。

### 下载

最新版 DMG 永远指向这条链接：

```
https://github.com/HMyaoyuan/whatsup-releases/releases/latest/download/WhatsUp.dmg
```

也可以直接去 [Releases 页面](https://github.com/HMyaoyuan/whatsup-releases/releases) 看历史版本和更新日志。

### 系统要求

- macOS 13 Ventura 及以上
- Apple Silicon 原生（M1 / M2 / M3 / M4）

### 安装

1. 下载 `WhatsUp.dmg`
2. 双击挂载，把 `What'sUp.app` 拖进「应用程序」
3. 第一次打开 macOS 会弹「无法验证」，到「系统设置 → 隐私与安全 → 仍要打开」放行一次即可
4. 菜单栏出现一只小鼠头像，就装好了

### 定价

- **免费试用 3 天**，全功能，不要邮箱不要账号
- **¥18 / $3 一次买断**，绑定当前 Mac 终身有效，v1.x 免费更新
- 购买入口：[findwhatsup.com/#pricing](https://findwhatsup.com/#pricing)

### 为什么是公开仓库但没有源码？

这个仓库只存签名+公证过的 DMG 构建产物、版本说明和自动更新的 appcast，不包含源代码。源码在另一个私有仓库里。

---

## English

### What is it?

The dev servers you started — `npm run dev`, `docker compose up`, `python manage.py runserver` — plus the ones Cursor / Claude Code / Codex quietly spun up on your behalf. Most people lose track of all of them.

**What'sUp** is a macOS menu-bar tool that inventories every running background process on your Mac, groups them by Git repo, flags duplicates and zombies, and lets you sweep them away in one click.

### Download

The latest DMG always lives here:

```
https://github.com/HMyaoyuan/whatsup-releases/releases/latest/download/WhatsUp.dmg
```

Or browse all versions on the [Releases page](https://github.com/HMyaoyuan/whatsup-releases/releases).

### Requirements

- macOS 13 Ventura or later
- Apple silicon only (M1 / M2 / M3 / M4)

### Install

1. Download `WhatsUp.dmg`
2. Mount it and drag `What'sUp.app` into `/Applications`
3. macOS's first-launch Gatekeeper: open **System Settings → Privacy & Security** and click **Open Anyway**
4. The mole in the menu bar means you're done

### Pricing

- **3-day free trial**, full feature set, no email, no account
- **¥18 / $3 one-time** — bound to this Mac for life, free v1.x updates
- Buy: [findwhatsup.com/#pricing](https://findwhatsup.com/#pricing)

### Why is this repo public but empty?

This repository only hosts the signed & notarised DMG builds, release notes and appcast for in-app updates. The source lives in a separate, private repository.

---

<sub>Copyright © 2026 HMyaoyuan. Binaries distributed from this repository are governed by the [EULA](https://findwhatsup.com/eula) shipped with each release. Redistribution requires written permission.</sub>
