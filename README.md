<div align="center">

# 📦 无敌（Wudibuddy）

> *"AI 帮你一个下午起十个项目，然后它们就再也找不到了。无敌 帮你把它们找回来。"*

**无敌：Agent 的驾驶舱。** 一边浏览、预览、编辑本地文件，一边在内嵌真实终端里指挥 Claude Code / Codex 干活，看清它碰过的每个文件、改过的每一行，随时接手。

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![macOS](https://img.shields.io/badge/macOS-arm64-blueviolet)](#下载安装)
[![Windows](https://img.shields.io/badge/Windows-x64-lightgrey)](#下载安装)

本仓库用于**分发安装包**（源码不开源）。macOS 与 Windows 两平台安装包见下方 [下载安装](#下载安装) / Release。

</div>

---

## 界面预览

<p align="center">
  <img src="docs/主界面.png" alt="无敌 主界面：左边文件浏览/预览/编辑，右边内嵌真实终端" width="95%">
</p>

<p align="center">
  <img src="docs/自定义模型.png" alt="无敌 模型设置：给本机 Claude Code / Codex 切换 API 底座" width="95%">
</p>

---

## 它能做什么

- **文件浏览与预览**：目录树、全局模糊搜索（`内容:` 前缀切全文搜索）、Markdown/代码/图片/视频/PDF 内嵌预览，Excel / Word / PPTX 也能直接看。
- **内嵌真实终端**：node-pty + xterm.js（WebGL 渲染），跑 Claude Code / vim / htop 不花屏。
- **指挥 Agent**：从文件列表拖文件进终端当上下文、选中文字即甩给终端、路径可点击；终端里的 agent 还能指挥兄弟窗口。
- **看 Agent 改了什么**：agent 每写一个文件，对应卡片亮起来；会话回放、Git diff、变更收件箱。
- **定时任务**：cron / 固定时刻 / 固定间隔，到点自动开终端跑 agent。
- **模型供应商**：给本机 Claude Code / Codex 切换 API 底座（对齐 CC Switch）。
- **本地优先**：零依赖后端、数据不出本机、离线完全可用。

## 下载安装

| 平台 | 安装包 | 说明 |
|---|---|---|
| **macOS** | `Wudibuddy-1.1.0-arm64.dmg` | 拖进「应用程序」即可，Apple Silicon 原生。当前未签名未公证（macOS 26 ad-hoc 签名会破坏 Electron 框架加载链），首次打开如被 Gatekeeper 拦 → 右键 → 打开 |
| **Windows** | `Wudibuddy-1.1.0-Windows-x64.exe` | 双击安装（或便携版免安装）。由 GitHub Actions 在真实 Windows 环境构建，node-pty 已原生编译。⚠️ 处于内测阶段，请自行评估后使用 |

> 到 [Releases](https://github.com/waytouniverse/wudi/releases) 页下载对应平台的安装包。

<details>
<summary>系统要求</summary>

- **macOS**：Apple Silicon (arm64)，macOS 12 或更新。
- **Windows**：64 位（x64），Windows 10 或更新。

</details>

## 关于

**无敌** 由 [阿旬同学](https://ai.wudiyuzhou.top/) 搭建，建立在多个开源项目之上，并非完全从零打造。

> 把大模型从 PPT 搬进生产线。不做「聊天气泡式」AI，只做能直接算 ROI 的落地场景。

- **角色**：AI 产品研发框架师 · 企业场景应用创新专家 · 算法工程师 · 珠海青年夜校讲师
- **个人站点**：[ai.wudiyuzhou.top](https://ai.wudiyuzhou.top/) · GitHub [@waytouniverse](https://github.com/waytouniverse)
- **License**: [MIT](LICENSE)

## 联系作者

<table align="center">
  <tr>
    <td align="center">
      <img src="docs/个人微信二维码.png" alt="个人微信二维码" width="190"><br>
      <b>加我的微信</b>
    </td>
    <td align="center">
      <img src="docs/微信公众号二维码.jpg" alt="微信公众号二维码" width="190"><br>
      <b>关注公众号</b>
    </td>
  </tr>
</table>

扫码添加微信，或关注公众号，获取更新与支持。

---

<div align="center">

MIT License © [阿旬同学](https://github.com/waytouniverse)

</div>
