# Xin · `xxkingstuggle`

专注 **AI Agent 工作流与多模型网关**、**macOS / iOS / Android 原生跨端工具** 与 **Web 全栈 / Chrome MV3 扩展开发**。  
具备覆盖 100+ 校区的 B2B2C AI 教育平台产品与研发协作经验，既能从业务痛点拆解数据字段、原型与验收标准，也能独立完成从架构设计、自动化测试到跨平台打包发版的端到端工程交付。

- 个人作品集与深度工程手记：[**myzjx.com**](https://myzjx.com)
- 软件作品与公开下载总览：[**myzjx.com/software**](https://myzjx.com/software/)
- 技术与产品专栏归档：[**myzjx.com/posts**](https://myzjx.com/posts/)

---

## 代表开源作品与 Release 矩阵

### 1. 原生桌面与跨端应用（macOS · iOS · Android）

| 项目 | 最新 Release | 技术栈 | 核心能力 |
|---|---|---|---|
| [**USB LinkMic**](https://github.com/xxkingstuggle/usblinkmic) | [`v4.0.17`](https://github.com/xxkingstuggle/usblinkmic/releases/tag/v4.0.17) | Swift · AppKit · Kotlin · ADB · USB NCM | 将 Android 手机接为 Mac 低延迟麦克风（USB / 局域网自动重连 + BlackHole），并在双端间实现 USB 双向供网与充电状态协商 |
| [**zjx-download**](https://github.com/xxkingstuggle/zjx-download) | [`v2.0.4`](https://github.com/xxkingstuggle/zjx-download/releases/tag/v2.0.4) | Swift · SwiftUI · Chrome MV3 · Native Messaging | macOS 原生多线程下载器，支持分片断点续传持久化、未知长度流回退续传、Chrome 浏览器下载接管与无头 CLI |
| [**HabitBloom**](https://github.com/xxkingstuggle/HabitBloom) | [`v1.0.0`](https://github.com/xxkingstuggle/HabitBloom/releases/tag/v1.0.0) | SwiftUI · SwiftData · WidgetKit · Cloudflare DO | 本地优先的习惯打卡与交互式桌面小组件工程，支持 App Group 共享容器与 Cloudflare Workers 远程快照双路径回并 |
| [**DimWallpaper**](https://github.com/xxkingstuggle/dim-wallpaper) | [`v1.0.0`](https://github.com/xxkingstuggle/dim-wallpaper/releases/tag/v1.0.0) | Swift · AppKit · CoreGraphics | 不改动系统壁纸文件，在 `.desktopWindow` 与桌面图标层之间挂载零交互穿透遮罩，实现深色模式自动压暗与多屏热插拔同步 |
| [**Xiaomi App Launcher**](https://github.com/xxkingstuggle/xiaomi-app-launcher) | [`v1.0.0`](https://github.com/xxkingstuggle/xiaomi-app-launcher/releases/tag/v1.0.0) | Kotlin · Jetpack Compose · JUnit | 极简 Android 应用启动器，纯本地毫秒级包名/应用名检索、置顶与使用频次排序，核心检索逻辑 100% JVM 单测覆盖 |

### 2. AI Agent 工作流、Skills 与多模型 API 网关

| 项目 | 最新 Release | 技术栈 | 核心能力 |
|---|---|---|---|
| [**思路导航 V3 (Thought Navigator)**](https://github.com/xxkingstuggle/thought-navigator-v3) | [`v3.0.1`](https://github.com/xxkingstuggle/thought-navigator-v3/releases/tag/v3.0.1) | Agent Skills · Codex Plugin · Prompt Routing | 将 25 个思考模型收拢为可安装的 Codex 插件，支持“任务按需自发现”与“显式路由导航”双模式及防过度设计停止条件 |
| [**Local Governance Skill**](https://github.com/xxkingstuggle/local-governance-skill) | [`v1.0.0`](https://github.com/xxkingstuggle/local-governance-skill/releases/tag/v1.0.0) | Agent Skill · Workspace Governance | 面向个人本机多仓库的 Agent 治理协议：通过不变式（Invariants）、三层生命周期账本与证据驱动门禁消除跨会话漂移 |
| [**ChatGPT Supervisor Prototype**](https://github.com/xxkingstuggle/chatgpt-supervisor-prototype) | [`v0.1.0`](https://github.com/xxkingstuggle/chatgpt-supervisor-prototype/releases/tag/v0.1.0) | Python · State Machine · Optimistic Lock | 跨会话长任务监督状态机 CLI 与 Skill：用不可变请求包、`state_version` 乐观锁与单执行器互斥锁协同高层规划与终端执行 |
| [**CPA Plugin**](https://github.com/xxkingstuggle/cpa-plugin) | `main` | Go · CGO · C ABI · OAuth / PAT | CLIProxyAPI 多模型网关动态插件集（WorkBuddy / CodeBuddy / QoderWork Provider），含 OAuth 鉴权、动态模型枚举与多平台构建 |
| [**BossHunter**](https://github.com/xxkingstuggle/BossHunter) | `main` | Python · Playwright · YAML Rule Engine | 具备反自动化节流、多简历画像匹配与本地 SQLite 幂等投递账本的智能求职 Agent |

### 3. Web 全栈与 Chrome MV3 扩展

| 项目 | 最新 Release | 技术栈 | 核心能力 |
|---|---|---|---|
| [**MYZJX (myzjx.com)**](https://github.com/xxkingstuggle/blog) | 线上运行 | Astro · TypeScript · Cloudflare Workers / D1 · Vercel | 个人作品台与私人工作区全栈平台：前台实现图片色彩采样玻璃态与响应式画廊；后台集成 GitHub OAuth、D1 乐观锁版本控制与冲突恢复 |
| [**Route Lens**](https://github.com/xxkingstuggle/route-lens) | [`v1.3.1`](https://github.com/xxkingstuggle/route-lens/releases/tag/v1.3.1) | JavaScript · Chrome MV3 · Shadow DOM · SSE | 在 ChatGPT Web 右侧窄栏实时拦截并对照请求与 SSE 响应流中的真实模型路由字段，识别静默降级与路由冲突 |
| [**Tintpane**](https://github.com/xxkingstuggle/tintpane) | [`v2.4.0`](https://github.com/xxkingstuggle/tintpane/releases/tag/v2.4.0) | JavaScript · Chrome MV3 · Dynamic Content Scripts | 为明确启用的 Chromium PWA 窗口动态注入 `theme-color`，支持域名树层级配置继承、焦点状态配色与双向别名同步 |

---

## 技术栈概览

- **AI 与 Agent 工程**：Codex / Claude Code、Agent Skills / MCP 编排、OpenAI / Anthropic 兼容网关（CLIProxyAPI / New API / Sub2API）、OAuth / PAT 鉴权协议、多模型容灾路由与自动化回归回滚
- **客户端与系统开发**：Swift（AppKit / SwiftUI / SwiftData / WidgetKit / Accessibility API / CoreGraphics）、Kotlin（Android AudioRecord / VPNService / Jetpack Compose）
- **Web 与云原生**：TypeScript / JavaScript、Astro、Cloudflare Workers / D1 / Durable Objects、Chrome Manifest V3、Go（CGO 插件）、Python、SQL、Docker / OrbStack
- **产品与工程方法**：B2B2C 多角色需求拆解、Figma 原型设计、P0–P2 问题分诊闭环、Playwright WebKit 自动化视觉与交互验收
