# Rain

Rain 是一个基于 libxposed 102 API 的现代 Xposed 模块，内置 Jetpack Compose + Miuix 管理界面。

模块在目标应用自己的进程里改写运行时行为，管理界面在模块自身进程里运行，两套代码互不依赖。当前适配应用列表以模块内的“应用”页面为准。

本 README 不列出具体目标应用与 Hook 细节，适配清单和推荐作用域以模块运行时展示为准。

## 功能特性

- 框架状态：展示 LSPosed 框架连接状态、版本与 API 信息
- 作用域同步：在模块内读取并同步 LSPosed 推荐作用域
- 外观设置：深色/浅色、Monet 取色、悬浮导航栏、预测返回、隐藏桌面图标
- 独立容错：每个 Hook 单独保护，目标应用混淆或版本漂移时只失效单项功能，不会拖垮目标应用进程
- 热重载：基于 libxposed 102 API 的 hook id 与 `autoHotReload`

## 环境要求

- Android 9（API 28）及以上；Hook 回调需要 API 29 及以上
- 支持 libxposed 102 API 的框架，例如 LSPosed
- 已解锁/root 设备

## 安装

1. 安装模块 APK
2. 在 LSPosed 中启用 Rain
3. 在模块内的“应用”页面或 LSPosed 中选择作用域
4. 按框架提示重启目标应用，或触发热重载

## 说明

仅供个人学习与技术研究使用，请在合规前提下使用。
