<h1 align="center">Hi 👋, I'm Sun1090</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&pause=1000&color=58A6FF&center=true&vCenter=true&width=620&lines=Frontend+Developer;Trading+%26+Charting+Tools;Vue+%C2%B7+React+%C2%B7+TypeScript;Loon+%C2%B7+Surge+%C2%B7+QuantumultX" alt="typing" />
</p>

<p align="center">
  <b>Frontend Developer</b> · Vue / React / TypeScript<br/>
  关注工程化、可视化图表、交易教育与独立开发产品化。
</p>

<p align="center">
  <a href="https://github.com/Sun1090?tab=repositories">Repositories</a> ·
  <a href="https://trade-buty.vercel.app">Trade Buty</a> ·
  <a href="https://kline-buty.vercel.app">Kline Buty</a> ·
  <a href="https://github.com/Sun1090/IndieStack">IndieStack</a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Sun1090&label=Profile+views&color=0e75b6&style=flat" alt="Profile views">
</p>

---

## 🧭 About Me

- 🔭 目前重点做 **交易教育 / 行情可视化** 方向的产品。
- 🧠 习惯把项目拆成可维护的模块：内容、图表、数据层、测试、部署和文档。
- 🛠️ 常用技术：**TypeScript、React、Vue3、Next.js、Vite、Tailwind CSS、Node.js**。
- 📈 对 **K 线图表、实时行情、历史回放、数据可视化** 很感兴趣。
- 🚀 也在研究可复用的 **独立开发启动模板**、**AI agent 规范模板（[agents-template](https://github.com/Sun1090/agents-template)）** 和 **Cloudflare Worker API 网关**。
- 🛡️ 熟悉 **Loon（主力）/ Surge / QuantumultX / Stash** 等代理工具生态，关注分流、复写与脚本的可维护性。
- 📫 联系方式：[Telegram 频道](https://t.me/lololoTotice) · [Telegram 机器人](https://t.me/info_lolo_bot) · [邮箱](mailto:register_kirito@163.com)。

---

## 🚦 Current Focus

| 方向 | 状态 | 说明 |
|---|---|---|
| Trade Buty | 🚧 Active | 免费中立的交易教育平台，课程 + 真实行情练习 |
| Kline Buty | 🚧 Active | 实时 K 线图表、技术指标、画线工具与历史回放 |
| cross-tab-worker-databus | 📦 Published | 跨标签页 Worker 集群数据总线（npm v0.21.4），SharedWorker / Dedicated / 主线程降级 |
| IndieStack | 🧩 Building | 独立开发者的生产级 Next.js / Supabase 启动模板 |
| agents-template | 🧪 Experimenting | AI agent 工程化规范模板（frontend / backend / fullstack 三套） |
| labor-dispatch-admin | 🛣 Roadmap v4 | Nuxt4 外包人事管理系统 v1.1.1，审批链引擎 + v4 hardening 路线图推进 |
| Frontend Archive | 🗂️ Maintained | 整理 Vue / React / 后台模板 / 可视化练习项目 |

---

## ⭐ Featured Projects

### 1. [Trade Buty](https://github.com/Sun1090/trade-buty)

> 免费中立的交易教育平台：**分级课程（学）× 真实行情图表与历史回放（练）**，不荐股、不导流、基础课程永久免费。

- 🎯 把交易知识的"学—练—测"串成闭环：课程阅读 → 行情练习 → 错题复盘，一条学习路径。
- 📚 课程知识库以 git submodule 引用 kline-buty，自建 content pipeline 渲染管线产出可索引内容，配目录 / 阅读时长 / 书签 / 术语表。
- 📊 币安 REST + WebSocket 真实行情嵌入课程，盲盒式历史回放训练 + 猜涨跌考核。
- ✅ 章节随堂测验 + **错题本** + AI 出题（题源可溯源 / 难度可配）+ 学习趋势统计 + 连续学习 / 每日目标 / 活动热力图；进度本地存储 + Supabase 云端同步 + 离线写入队列。
- 🔐 账号与合规闭环：本地数据导出、账号删除；R10 内容运营门禁（双语标题/术语一致性、SEO hreflang、搜索同义与纠错改写）。
- 🤖 内置 AI 陪学（ai-chat），错题驱动出题 + RAG 方向预留。
- 🌐 中英双语，移动端适配到 320px。
- ⚙️ **Next.js 16 · React 19 · TypeScript · Tailwind v4 · lightweight-charts v5**；构建时 JSON 索引 + 客户端检索；Vitest · Playwright 视觉审计 · CI；**R7 性能预算门禁**（per-route JS budgets + AI chunk isolation + fps degrade）。

### 2. [Kline Buty](https://github.com/Sun1090/kline-buty)

> 免 API Key 的开源实时 K 线图表，币安公开数据驱动。

- 🎯 自研交互与渲染适配层的图表内核：回放 / 盘口 / 画线 / 指标各自是纯逻辑引擎，与渲染解耦、可单测。
- 🕯️ 蜡烛 / 折线 / 面积图，14 档周期（1s–1M）；**49 种画线工具**（趋势线 / 通道 / 斐波那契 / 江恩 / 楔形 / R:R / 文本标注等）+ 图层管理 + 模板保存/应用与社区导入导出。
- 📈 **26 个指标引擎**（BOLL / Ichimoku / MACD / KDJ / RSI / SAR / Supertrend / VWAP 等），参数可调 + 趋势/波动率智能推荐。
- 🧾 orderbook 聚合 + 深度曲线 + 成交量分布独立计算；1/2/4 多图同屏。
- ⏪ 历史回放是纯状态机（cursor 推进 / 跳转 / 到顶暂停，1x–50x）；模拟仓位盈亏、价格提醒（含 ATR 波动率自适应）、订单逻辑各自独立。
- 🌐 五语 i18n（中 / 英 / 日 / 韩 / 西）+ PWA 可安装离线；深链分享、图表快照画廊、应用内文档索引。
- 🛠️ 自研交互层：视域裁剪、惯性滚动、捏合缩放、触屏手势；渲染引擎可替换。
- ⚙️ **React 19 · TypeScript 6 · Vite 8 · lightweight-charts v5**；K 线 store 幂等合并、WS 心跳重连 + 断线回填；1500+ 单测 + Playwright 三浏览器 E2E + CodeQL / dependabot 安全门禁。

### 3. [cross-tab-worker-databus](https://github.com/Sun1090/cross-tab-worker-databus)

> 框架无关的浏览器跨标签页数据总线，原生 Web Worker / SharedWorker / Centrifuge / 零依赖 WebSocket 全支持。

- 🎯 让应用只关心订阅 Topic 与处理数据，跨标签页的 Worker 集群、Topic 所有者复用、负载均衡、故障迁移、页面生命周期全部内置。
- 🔌 `workerMode` 支持 `dedicated` / `shared` / `auto`：`auto` 按 SharedWorker → Dedicated Worker → 主线程 WebSocket 自动降级，反之亦可显式降级。
- 🧩 同源标签页通过 BroadcastChannel 组成逻辑 Worker 集群；sticky Topic 所有者 + 订阅复用 + 新 Topic 负载分配 + 失败迁移，新进 Topic 自动落到负载最低的 Worker。
- 📡 可选 Centrifuge 传输（`cross-tab-worker-databus/centrifuge`）+ 零依赖原生 WebSocket 传输（`createWebSocketDataBus`）；传输支持 `publishBatch` 批量帧，单条 `publish` 自动兜底。
- 🪝 React/Vue 3 适配器新增 `useCrossTabHealth` 健康轮询；Transferable ArrayBuffer、消息回放留存、通配符订阅、可观测追踪快照。无 BroadcastChannel 时可选 `storage-event` 信道降级（opt-in）。
- ⚙️ **TypeScript · Web Worker · SharedWorker · BroadcastChannel · Centrifuge**；零运行时核心依赖（Centrifuge 传输仅 peer），已发布 **npm v0.21.4**（含热路径性能门禁 + Worker backend 能力嗅探）。

### 4. [IndieStack](https://github.com/Sun1090/IndieStack)

> 面向独立开发者的生产级 Next.js 启动模板（v0.11.0），开箱即用、可直接部署。

- 🎯 把 SaaS 从 0 到上线要重复做的事（认证 / 多租户 / 计费 / 监控 / 营销页 / 对象存储 / APM）预先做好，省去重复搭脚手架。
- 🔐 Supabase SSR Auth（Email / GitHub / Google）+ **TOTP/MFA** + **WebAuthn/Passkey**（feature flag 门控）+ 会话设备列表与单设备吊销；PostgreSQL RLS + 多租户团队与角色邀请。
- 💳 Stripe-ready 订阅计费；Dashboard 预置 Overview / Analytics / Team / Billing / API Keys / Projects / Admin；**阿里云 OSS / Supabase Storage 双驱动对象存储**。
- 📄 `(marketing)` 路由组：blog / pricing / contact / changelog / faq / about——落地页与法律页齐备。
- 🛡️ **Sentry + Appark APM**（无厂商 SDK、旁路关闭）；安全 Header、限流、邮件通道完善（类型折叠 / 失败重试 / digest 时区错峰）。
- ⚙️ **Next.js 16 App Router · RSC + Server Actions · shadcn/ui · Supabase · Tailwind v4 原生主题**；Vitest + Playwright E2E + CI；TanStack Query 缓存档位化（live/standard/admin）；**单元/组件测试门禁 + 覆盖率阈值化**；内联 `/docs` + 独立 VitePress 文档站。

### 5. labor-dispatch-admin 🔒 <sub>私有项目 · Client Work</sub>

> 外包公司人事管理系统，基于 Nuxt4 全栈。

- 🎯 覆盖外包人事全流程：人员档案、部门岗位、考勤请假、合同、**审批链引擎**、RBAC 权限。
- 🔁 审批工作流：链式审批定义 CRUD、跨链决策、分级 SLA 与超时队列、驳回后重提开启新链。
- 🔐 安全闭环：bcrypt + JWT 会话、强制改密、路由鉴权；服务端强制授权，前端权限仅做 UX 控制。
- ⚙️ **Nuxt4 · Vue3 · TypeScript · Drizzle ORM · PostgreSQL · Redis · reka-ui · ECharts**；Vitest + Playwright E2E + CI + AGENTS.md 规范。

---

## 🧑‍💻 Frontend & Learning Projects

### Original & Learning Projects

| 项目 | 类型 | 最后活跃 | 简介 | 技术关键词 |
|---|---|---|---|---|
| [IndieStack](https://github.com/Sun1090/IndieStack) | Original | 2026-09 | 独立开发者生产级 Next.js 启动模板 | Next.js, TypeScript, Supabase |
| labor-dispatch-admin 🔒 | Original（私有） | 2026-09 | Nuxt4 外包人事管理系统 | Nuxt4, TypeScript, Drizzle, PostgreSQL |
| [trade-buty](https://github.com/Sun1090/trade-buty) | Original | 2026-09 | 免费中立交易教育平台 | Next.js, React, TypeScript |
| [kline-buty](https://github.com/Sun1090/kline-buty) | Original | 2026-09 | 自研交互内核的 K 线图表，画线/指标/回放/盘口各自独立引擎 | React, TypeScript, lightweight-charts |
| [cross-tab-worker-databus](https://github.com/Sun1090/cross-tab-worker-databus) | Original | 2026-09 | 跨标签页 Worker 集群数据总线，SharedWorker→Dedicated→主线程降级，支持 Centrifuge | TypeScript, Web Worker, SharedWorker |
| [nuxt-admin-template](https://github.com/Sun1090/nuxt-admin-template) | Original | 2026-09 | Nuxt + Drizzle + shadcn-vue 可复用后台模板 | Vue, TypeScript, Nuxt |
| [agents-template](https://github.com/Sun1090/agents-template) | Original | 2026-09 | AI agent 工程化规范模板（frontend / backend / fullstack） | Markdown, AI Agents |
| [danmu_api](https://github.com/Sun1090/danmu_api) | Original | 2025-09 | 弹幕相关 API 服务 | JavaScript, Vercel |

### Selected Forks & Template References

| 项目 | 类型 | 用途 | 上游方向 |
|---|---|---|---|
| [CPA-Manager-Plus](https://github.com/seakee/CPA-Manager-Plus) | Fork | AI 网关管理面板与请求/用量/成本/配额观测参考 | Go, Node.js |
| [soybean-admin-element-plus](https://github.com/Sun1090/soybean-admin-element-plus) | Fork | 后台模板参考 | Vue3, Element Plus |
| [vue-vben-admin](https://github.com/Sun1090/vue-vben-admin) | Fork | 后台架构参考 | Vue3, Vite, TypeScript |
| [antdv-pro](https://github.com/antdv-pro/antdv-pro) | Fork | Ant Design Vue 模板参考 | Vue, Ant Design Vue |
| [stepin-template-js](https://github.com/stepui/stepin-template-js) | Fork | 后台模板参考 | Vue, Ant Design Vue, Tailwind |
| [Vue-mmPlayer](https://github.com/Sun1090/Vue-mmPlayer) | Fork | 音乐播放器实现参考 | Vue2 |
| [aurora-public](https://github.com/Sun1090/aurora-public) | Fork | 全栈博客系统参考 | Vue, Spring Boot |
| [ios_rule_script](https://github.com/Sun1090/ios_rule_script) | Fork | 分流 / 复写 / 脚本规则学习 | JavaScript, Python |
| [transfer-api](https://github.com/Sun1090/transfer-api) | Fork | Cloudflare Worker API 转发网关 | Cloudflare Workers |

---

## 🤝 Community Contributions

- ✅ **3 个上游开源 PR 已合并**：antdv-pro ×2、stepin-template-js ×1；自有仓库保持日常 PR 传输（labor-dispatch-admin 累计合入 40+ PR）。
- 🐞 在开源项目里提交过 **69 个 Issue**：其中 **51 个已关闭 / 18 个仍开放**。

### Merged Pull Requests

#### Upstream（开源贡献）

| 仓库 | PR | 内容 |
|---|---|---|
| [antdv-pro](https://github.com/antdv-pro/antdv-pro) | [#151](https://github.com/antdv-pro/antdv-pro/pull/151) | 修复路由切换导致 page-container 头部面包屑等区域被意外隐藏 |
| [antdv-pro](https://github.com/antdv-pro/antdv-pro) | [#84](https://github.com/antdv-pro/antdv-pro/pull/84) | 调整侧边栏可伸缩按钮位置 |
| [stepin-template-js](https://github.com/stepui/stepin-template-js) | [#1](https://github.com/stepui/stepin-template-js/pull/1) | 更新文档说明 |

#### Own Repos（自有仓库工程化提交）

| 仓库 | PR | 内容 |
|---|---|---|
| labor-dispatch-admin 🔒 | #4 | 通知、报表、打卡、全局搜索与会话交互优化 |
| labor-dispatch-admin 🔒 | #3 | RB 验收 E2E 自动化、强制改密流程与缓存加固 |
| labor-dispatch-admin 🔒 | #2 | 修正路由鉴权与根导航跳转 |
| labor-dispatch-admin 🔒 | #1 | 安全加固、CI 流水线、AGENTS.md 与部署准备 |

#### Unmerged（未合并）

| 仓库 | PR | 内容 |
|---|---|---|
| [kline-buty](https://github.com/Sun1090/kline-buty) | [#1](https://github.com/Sun1090/kline-buty/pull/1) | Capacitor 壳工程落地、app 分支闭环 |
| [aurora](https://github.com/linhaojun857/aurora) | [#11](https://github.com/linhaojun857/aurora/pull/11) | 补充 aurora-blog 下缺少的依赖 |

### Issue Reporting Highlights

| 项目 | 数量 | 关注点 |
|---|---|---|
| [soybean-admin-element-plus](https://github.com/soybeanjs/soybean-admin-element-plus) | 29 | 后台路由、菜单、标签页、主题与交互细节 |
| [UHDadmin-feedback](https://github.com/fxxkrlab/UHDadmin-feedback) | 26 | 权限、状态刷新、主题一致性、空态与交互反馈 |
| [stepin-template](https://github.com/stepui/stepin-template) | 8 | 布局、路由配置、图标、导航模式 |
| 其它开源项目 | 6 | Ant Design Vue、Hackintosh、pnpm 等使用反馈 |

---

## 🌐 Live Deployments

| 项目 | 类型 | 在线入口 | 说明 |
|---|---|---|---|
| [Trade Buty](https://trade-buty.vercel.app) | Web App | Open App | 免费交易教育平台，含课程与练习 |
| [Kline Buty](https://kline-buty.vercel.app) | Web App | Open App | 实时 K 线图表与历史回放 |
| [IndieStack](https://indie-stack-theta.vercel.app) | Template Demo | Open Demo | 独立开发启动模板演示 |
| [IndieStack Docs](https://indie-stack-docs-site.vercel.app) | Docs | Read Docs | IndieStack 双语文档站 |
| [labor-dispatch-admin](https://labor-dispatch-admin-pink.vercel.app) | Admin App | Open App | Nuxt4 外包人事管理系统演示 |
| [Kline Knowledge](https://kline-buty.vercel.app/knowledge/) | Knowledge Base | Read Docs | Kline Buty 配套知识库 |
| [danmu_api](https://danmuapi-amber.vercel.app) | API Service | Check Service | 弹幕相关 API 服务 |

---

## 🧰 Tech Stack

### Languages & Frameworks

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Vue](https://img.shields.io/badge/Vue3-35495E?style=flat&logo=vuedotjs&logoColor=4FC08D)
![Next.js](https://img.shields.io/badge/Next.js-black?style=flat&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)

### UI & Styling

![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn/ui-000000?style=flat&logo=shadcnui&logoColor=white)
![Element Plus](https://img.shields.io/badge/Element_Plus-409EFF?style=flat&logo=element&logoColor=white)
![Ant Design](https://img.shields.io/badge/Ant_Design-0170FE?style=flat&logo=antdesign&logoColor=white)

### Data & Infra

![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Drizzle ORM](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat&logo=drizzle&logoColor=black)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat&logo=cloudflare&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

### Charting & Product Tools

![lightweight-charts](https://img.shields.io/badge/lightweight--charts-2962FF?style=flat&logo=chartdotjs&logoColor=white)
![ECharts](https://img.shields.io/badge/ECharts-AA344D?style=flat&logo=apacheecharts&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat&logo=sentry&logoColor=white)

---

## 🛡️ Proxy & Network Tools

### iOS 代理客户端（主力与常用）

| 工具 | 定位 | 说明 |
|---|---|---|
| <a href="https://nsloon.app" target="_blank">**Loon**</a> | ⭐ 主力 | 脚本、复写、分流、插件式订阅，日常自用主力 |
| <a href="https://nssurge.com" target="_blank">Surge</a> | 常用 | 老牌抓包与代理工具，规则生态完善 |
| <a href="https://apps.apple.com/app/quantumult-x/id1442367847" target="_blank">Quantumult X</a> | 常用 | 圈 X，分流 / 复写 / Task 脚本生态活跃 |
| <a href="https://stash.wiki" target="_blank">Stash</a> | 常用 | 兼容 Clash 配置的 iOS / macOS 客户端 |

### 桌面 / 安卓常用客户端

| 项目 | 平台 | 说明 |
|---|---|---|
| <a href="https://github.com/clash-verge-rev/clash-verge-rev" target="_blank">clash-verge-rev</a> | Win / macOS / Linux | 基于 Tauri 的现代 GUI 客户端，体验打磨细致 |
| <a href="https://github.com/mihomo-party-org/clash-party" target="_blank">clash-party</a> | Win / macOS / Linux | 又一个 mihomo GUI，轻量好用 |
| <a href="https://github.com/MatsuriDayo/NekoBoxForAndroid" target="_blank">NekoBoxForAndroid</a> | Android | sing-box / 通用代理工具链，安卓端主力之一 |

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://awesome-github-stats.azurewebsites.net/user-stats/Sun1090?theme=tokyonight&cardType=level&hide_border=true" alt="GitHub level card" height="165em">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Sun1090&theme=tokyonight" alt="GitHub stats" height="165em">
</div>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Sun1090&theme=tokyonight" alt="Repos per language" height="165em">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Sun1090&theme=tokyonight" alt="Most commit language" height="165em">
</div>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Sun1090&theme=tokyonight&utcOffset=8" alt="Productive time" height="165em">
  <img src="https://streak-stats.demolab.com?user=Sun1090&locale=en&hide_border=true&theme=tokyonight" alt="GitHub streak" height="165em">
</div>

---

<!-- 
Sun1090/Sun1090
This README is maintained locally and will be published as the GitHub profile README.
-->
