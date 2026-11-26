# Xin (`@xxkingstuggle`) · [myzjx.com](https://myzjx.com)

独立开发一些自己日常会用的小工具，主要写 **macOS / iOS / Android 原生应用**、**Chrome 扩展**，也折腾 **AI Agent 工作流与接口代理**。平时做产品、画原型，也自己把代码写完、测完并打包发布。

- 个人主页：[**myzjx.com**](https://myzjx.com)
- 软件合集与下载：[**myzjx.com/software**](https://myzjx.com/software/)
- 文章与随记：[**myzjx.com/posts**](https://myzjx.com/posts/)

---

## 开源项目

### 桌面与移动应用

| 项目 | 版本 | 技术栈 | 说明 |
|---|---|---|---|
| [**DimWallpaper**](https://github.com/xxkingstuggle/dim-wallpaper) · [介绍](https://myzjx.com/software/dim-wallpaper/) | [`v2.2.0`](https://github.com/xxkingstuggle/dim-wallpaper/releases/tag/v2.2.0) | Swift 6 · AppKit · SwiftUI · Core Animation | macOS 菜单栏调暗工具，无需额外权限；支持壁纸压暗（图标保持原亮）和后台窗口专注遮罩，菜单栏背景与桌面一体变暗而文字图标保持亮色，支持 `0.08s–2.00s` 自定义时长和 6 种过渡动效 |
| [**zjx-download**](https://github.com/xxkingstuggle/zjx-download) · [介绍](https://myzjx.com/software/zjx-download/) | [`v2.0.6`](https://github.com/xxkingstuggle/zjx-download/releases/tag/v2.0.6) | Swift 6 · SwiftUI · Chrome MV3 | macOS 多线程下载器与配套 Chrome 扩展，支持分片断点续传、未知长度流回退、跨域请求头清理和命令行调用 |
| [**USB LinkMic**](https://github.com/xxkingstuggle/usblinkmic) · [介绍](https://myzjx.com/software/usblinkmic/) | [`v4.0.18`](https://github.com/xxkingstuggle/usblinkmic/releases/tag/v4.0.18) | Swift · AppKit · Kotlin · ADB | 把 Android 手机当作 Mac 的低延迟麦克风使用（支持 USB 与局域网自动重连，搭配 BlackHole），附带 USB 反向共享网络与日志排查工具 |
| [**HabitBloom**](https://github.com/xxkingstuggle/HabitBloom) · [介绍](https://myzjx.com/software/habitbloom/) | [`v1.1.0`](https://github.com/xxkingstuggle/HabitBloom/releases/tag/v1.1.0) | SwiftUI · SwiftData · Mac Catalyst · WidgetKit · Cloudflare | 本地优先的习惯打卡应用，支持 iOS、Mac 桌面端与交互式小组件，可按需通过 Cloudflare 同步备份 |
| [**FrameLit**](https://myzjx.com/software/framelit/) | [项目页](https://myzjx.com/software/framelit/) | Swift · AppKit · Accessibility API | macOS 原生窗口网格排版工具，支持自定义网格尺寸和快捷键快速摆放窗口 |
| [**Xiaomi App Launcher**](https://github.com/xxkingstuggle/xiaomi-app-launcher) | [`v1.0.0`](https://github.com/xxkingstuggle/xiaomi-app-launcher/releases/tag/v1.0.0) | Kotlin · Jetpack Compose | 轻量 Android 应用启动器，本地即时搜索应用名和包名，支持置顶与按使用频率排序 |

### AI 工具与工作流

| 项目 | 版本 | 技术栈 | 说明 |
|---|---|---|---|
| [**思路导航 V3 (Thought Navigator)**](https://github.com/xxkingstuggle/thought-navigator-v3) · [介绍](https://myzjx.com/software/thought-navigator/) | [`v3.0.1`](https://github.com/xxkingstuggle/thought-navigator-v3/releases/tag/v3.0.1) | Agent Skills · Codex Plugin | 把 25 个常用思考框架做成 Codex 插件，写方案或理思路时可按问题自动挑选或手动点选 |
| [**Local Governance Skill**](https://github.com/xxkingstuggle/local-governance-skill) | [`v1.0.0`](https://github.com/xxkingstuggle/local-governance-skill/releases/tag/v1.0.0) | Agent Skill | 用来整理本机多个代码仓的协作约定与变更记录，减少长时间跨会话开发时跑偏 |
| [**ChatGPT Supervisor Prototype**](https://github.com/xxkingstuggle/chatgpt-supervisor-prototype) | [`v0.1.0`](https://github.com/xxkingstuggle/chatgpt-supervisor-prototype/releases/tag/v0.1.0) | Python · CLI | 长任务协作原型：通过版本号锁与任务状态文件，让规划会话和执行终端配合推进多步任务 |
| [**CPA Plugin**](https://github.com/xxkingstuggle/cpa-plugin) | `main` | Go · CGO | 给 CLIProxyAPI 写的几个上游渠道插件（WorkBuddy / CodeBuddy / QoderWork），包含登录鉴权与模型列表同步 |
| [**BossHunter**](https://github.com/xxkingstuggle/BossHunter) | `main` | Python · Playwright · SQLite | 基于规则配置与本地去重记录的求职筛选辅助脚本，带请求频率控制 |

### Web 与浏览器扩展

| 项目 | 版本 | 技术栈 | 说明 |
|---|---|---|---|
| [**myzjx.com**](https://github.com/xxkingstuggle/blog) · [访问](https://myzjx.com) | 线上运行 | Astro · TypeScript · Cloudflare Workers / D1 · Vercel | 个人网站与软件发布页，包含作品展示、文章归档和简单的后台编辑管理 |
| [**Route Lens**](https://github.com/xxkingstuggle/route-lens) · [介绍](https://myzjx.com/software/route-lens/) | [`v1.3.2`](https://github.com/xxkingstuggle/route-lens/releases/tag/v1.3.2) | JavaScript · Chrome MV3 · Shadow DOM | 在 ChatGPT 网页侧边栏显示每次请求与响应里实际命中的模型字段，导出记录时自动脱敏 |
| [**TintPane**](https://github.com/xxkingstuggle/tintpane) · [介绍](https://myzjx.com/software/tintpane/) | [`v2.5.0`](https://github.com/xxkingstuggle/tintpane/releases/tag/v2.5.0) | JavaScript · Chrome MV3 | 给 Chromium PWA 窗口自定义标题栏 `theme-color`，支持按域名继承规则、焦点变色与弹窗实时预览 |

---

## 常用技术栈

- **客户端**：Swift（AppKit / SwiftUI / SwiftData / WidgetKit / CoreGraphics）、Kotlin（Android / Jetpack Compose）
- **Web 与扩展**：TypeScript / JavaScript、Astro、Chrome Manifest V3、Cloudflare Workers / D1
- **后端与脚本**：Go、Python、SQL、Playwright、Docker / OrbStack
- **AI 工具链**：Codex / Claude Code、Agent Skills / MCP、OpenAI / Anthropic 兼容代理接口

---

**Xin (`@xxkingstuggle`)** · [**myzjx.com**](https://myzjx.com)
