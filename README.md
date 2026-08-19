<div align="center">
<h1>Rain</h1>

<a href="https://github.com/Xposed-Modules-Repo/love.nairain.hook/releases"><img alt="GitHub all releases" src="https://img.shields.io/github/downloads/Xposed-Modules-Repo/love.nairain.hook/total?label=Downloads"></a>
<a href="https://github.com/Xposed-Modules-Repo/love.nairain.hook/releases/latest"><img alt="GitHub latest release" src="https://img.shields.io/github/v/release/Xposed-Modules-Repo/love.nairain.hook"></a>

<a href="https://t.me/Rain_Cl"><img alt="Telegram Channel" src="https://img.shields.io/badge/Telegram-频道-blue.svg?logo=telegram"></a>

<p>用于优化部分 App 使用体验的 Xposed 模块</p>

<p>

---

模块在目标应用自己的进程里改写运行时行为。当前适配应用列表以模块内的“应用”页面为准。

本 README 不列出具体目标应用与 Hook 细节，适配清单和推荐作用域以模块运行时展示为准。

## 功能特性

- 框架状态：展示 LSPosed 框架连接状态、版本与 API 信息
- 作用域同步：在模块内读取并同步 LSPosed 推荐作用域
- 外观设置：深色/浅色、Monet 取色、悬浮导航栏、隐藏桌面图标
- 独立容错：每个 Hook 单独保护，目标应用混淆或版本漂移时只失效单项功能，不会拖垮目标应用进程

## 环境要求

- Android 9（API 28）及以上
- 支持 libxposed 102 API 的框架，例如 LSPosed
- 已解锁/root 设备

## 使用教程

1. 安装模块 APK
2. 在 LSPosed 中启用 Rain
3. 在模块内的“应用”页面或 LSPosed 中选择作用域
4. 按框架提示重启目标应用
5. 也可参考应用内使用教程

## 说明

- 应用内所有功能仅供学习交流与技术研究使用，请勿用于商业或违法用途
- 本模块完全免费使用，不存在收费盈利
- 禁止售卖、倒卖或二次打包分发本模块
- 因使用本模块产生的任何后果，由使用者自行承担
- 如有侵权问题，请联系邮箱：nairain233@gmail.com
