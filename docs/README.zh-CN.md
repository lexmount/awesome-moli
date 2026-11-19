# Awesome Moli [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
  <a href="../README.md">English</a> | <strong>简体中文</strong> | <a href="README.ja.md">日本語</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.es.md">Español</a> | <a href="README.ko.md">한국어</a>
</p>

> 围绕 [Moli](https://github.com/lexmount/moli) 的工具、集成与应用示例。Moli 是面向 AI Agent 的开源无头浏览器。

探索 Moli 在浏览器自动化、网页提取、Agent 工作流与自托管服务中的用法。部分集成为可选功能或实验实现，请按各项目的指南配置。

## 目录

- [官方资源](#official-resources)
- [Fork 与二次开发](#forks-and-derivatives)
- [浏览器工具与 MCP](#browser-tools-and-mcp)
- [Agent 与工作区](#agents-and-workspaces)
- [网页提取与研究](#web-extraction-and-research)
- [测试与 QA](#testing-and-qa)
- [部署与打包](#deployment-and-packaging)
- [实验与开发案例](#experimental-and-development-examples)

<a id="official-resources"></a>

## 官方资源

- [Moli](https://github.com/lexmount/moli) - 官方仓库，包含安装说明、CLI 用法与自动化协议文档。
- [Releases](https://github.com/lexmount/moli/releases) - 预编译二进制与上游发布说明。
- [Agent skills](https://github.com/lexmount/moli/tree/main/skills) - 官方 Agent 技能，覆盖网页抓取、网页搜索与 CDP 服务启动。
- [WebMCP playground](https://github.com/lexmount/moli/tree/main/moli-playground/webmcp) - 通过 Moli 发现并调用网站原生 WebMCP 工具的脚本与演示。
- [Webstone](https://github.com/lexmount/webstone) - 浏览器与网页工具评测框架，提供可复现任务和执行证据。

<a id="forks-and-derivatives"></a>

## Fork 与二次开发

- [Limo](https://github.com/Spxg/limo) - 在终端直接用 Moli 提供的完整浏览器 Web API 环境运行 JavaScript。一个 `.js` 脚本就能用 `document` 创建按钮、监听并触发点击事件。
- [moli-stealth](https://github.com/Stravia-AI/moli-stealth) - Moli 的社区 fork。HTTP 和 WebSocket 共用一套 Rust 网络层，网络配置以 Chrome 为参照。
- [pilot](https://github.com/WSAdam/pilot) - 基于 Moli 二次开发的浏览器，可由 Playwright 和 Playwright MCP 直接启动，还能打开窗口观看 Agent 操作网页。 [Playwright 接入指南](https://github.com/WSAdam/pilot/blob/main/pilot/README.md)

<a id="browser-tools-and-mcp"></a>

## 浏览器工具与 MCP

- [Browser Bridge for Muse](https://github.com/rehantheorylab-pixel/browser-bridge-for-muse) - 浏览器自动化桥接工具，通过 Playwright/CDP 提供可选的 Moli 后端。
- [chatctl](https://github.com/ironpark/toolz/tree/main/cli/chatctl) - 管理聊天网页会话的 Go CLI，使用 Moli 进行无头访问、Chrome 处理交互式登录。
- [Delta Browser](https://github.com/DevAnimecx/deltabrowser) - MCP 浏览器服务，在 Linux x86_64 上提供托管 Moli 引擎与沙箱工作进程。
- [dsh-moli](https://github.com/27painter/dsh-moli) - DeepSeek Harness 社区插件，支持网页提取、JavaScript 求值、截图、PDF 和引擎诊断。
- [Moli Job Apply](https://github.com/mcaupybugs/claude-job-apply-skill-moli) - 实验性求职技能，通过 Moli 填写申请表单，提交前要求用户确认。
- [Moli Web Research](https://github.com/assistifyai405/moli-webonderzoek) - 本地 MCP 研究工具，可读取指定网址、保留来源证据并比较页面快照，目前为 beta。
- [Smart Tool](https://github.com/AllanSantos-DV/smart-tool-dist) - Windows Agent 工具分发包，在 HTTP 提取不足时使用 Moli 渲染 JavaScript 页面，并提供 Chromium 回退。

<a id="agents-and-workspaces"></a>

## Agent 与工作区

- [A3S Code](https://github.com/A3S-Lab/Code) - Agent 框架，为无头网页搜索后端配置经过校验的 Moli 运行时。
- [agent-fabric](https://github.com/BlueTeam-OU/agent-fabric) - 编码 Agent 控制平台，使用 Moli 读取网页，并通过 Playwright MCP 为各 Agent 提供脚本浏览。
- [agnostic-router-kit](https://github.com/adelvillar1/agnostic-router-kit) - Agent 工作流工具包，优先使用 Moli 渲染网页，再回退到自托管 Firecrawl 和普通 HTTP。
- [AION](https://github.com/JayCRL/AION) - Agent 基础设施，通过 web.read 工具调用 Moli，返回渲染后的 Markdown 或结构化 DOM 数据。
- [dsh-qq-bot](https://github.com/arrow1031-dev/dsh-qq-bot) - QQ 机器人接入项目，为 qq_webfetch 工具提供可选的本地 Moli 网页渲染路径。
- [Internkim](https://github.com/yeomyeonggeori/internkim) - 团队 Agent 工作区，提供用于公共网页浏览的 Moli 运行时。
- [Lumen](https://github.com/Andrea17982/Lumen) - 桌面 Agent 工作区，捆绑 Moli，并在多个模型及 CLI 适配器间共享浏览器工具。
- [mem0-omp](https://github.com/millianlmx/mem0-omp) - 编码 Agent 运行框架，提供容器化 Moli 浏览器及带认证的 HTTP/WebSocket CDP 网关。
- [Qianxun](https://github.com/imxood/qianxun) - 面向 DeepSeek Harness 的 Tauri 桌面工作台，支持本地 Moli 可执行文件探测与版本检查。
- [Relay](https://github.com/arcwright42/Relay) - Agent 运行时，提供有超时与输出限制的 Moli 网页抓取和浏览器安装管理。
- [Wick](https://github.com/yogasw/wick) - Go Agent 宿主，提供可选的 Moli 浏览器连接器、CDP 会话和 Markdown 提取。

<a id="web-extraction-and-research"></a>

## 网页提取与研究

- [888-url2md](https://github.com/tbdavid2019/888-url2md) - 网页转 Markdown 服务，提供本地 Moli CDP 后端和独立的 Chrome 回退策略。
- [A3S Search](https://github.com/A3S-Lab/Search) - 可嵌入的搜索引擎，提供 Moli CLI 渲染适配器与渲染并发限制。
- [Brains](https://github.com/YuniqueUnic/brains) - 带版本管理的 Markdown 知识库，可在导入网址时选择 Moli 渲染。
- [CTI Expert](https://github.com/7onez/cti-expert) - 威胁情报工具包，使用 Moli 提取 JavaScript 渲染后的 DOM，保留 Chromium 处理视觉证据。
- [HEIS](https://github.com/u4399com-beep/heis) - 小说采集系统，通过 Go HTTP 桥接服务封装 Moli 抓取和脚本求值。
- [hermes-dev](https://github.com/Sucotasch/hermes-dev) - Hermes 研究工具，将 Moli 渲染加入网页读取的回退链。
- [Lens](https://github.com/bysages/lens) - TypeScript 网页工具集，通过 CDP 使用 Moli 进行截图和页面读取。
- [ModalPrism](https://github.com/MistLoom/ModalPrism) - Rust 数据采集系统，通过浏览器访问器调用 Moli CLI 渲染动态网页。
- [molisnap](https://github.com/7a6163/molisnap) - 面向搜索爬虫和 AI bot 的 SPA 预渲染服务，支持缓存与 sitemap 预热。
- [PageSift](https://github.com/YOLOW92/pagesift) - Rust 网页与文档提取服务，将 Moli 纳入 Lightpanda → Moli → Chrome 浏览器选择链。
- [stvdy](https://github.com/jettapindika/stvdy) - 学习工作区，通过 Exa、Moli 和 HTTP/readability 回退链导入网页资料。
- [Vanilla](https://github.com/easylearnfromtw/vanilla) - 家庭 AI 工作区，提供需显式启用的 Moli 网页提取适配器，要求单独配置出站网络隔离。

<a id="testing-and-qa"></a>

## 测试与 QA

- [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - 端到端测试框架，提供实验性 Moli helper，支持本地进程管理和连接已有 CDP 端点。
- [KMJ CodeBridge](https://github.com/kmjtechno/kmj-codebridge) - MCP 开发工具包，可用 Moli 检查固定公共页面的提取结果，并回退到 Chrome 视觉 QA。

<a id="deployment-and-packaging"></a>

## 部署与打包

社区维护的安装配方与部署模板。

- [1Panel App](https://github.com/skingko/1panel_app/tree/localApps/apps/x-moli) - 社区维护的 Moli 1Panel 应用配方与 Docker 镜像构建。
- [A3S CLI](https://github.com/A3S-Lab/CLI) - A3S 命令行分发包，捆绑面向各目标平台的 Moli 运行时。
- [Homebrew Moli](https://github.com/hoishing/homebrew-moli) - 社区 Homebrew tap，安装 Moli 二进制及对应版本的官方 Agent 技能。
- [Lattice](https://github.com/mytecor/lattice/tree/main/profiles/moli) - NixOS Moli 服务，提供远程 CDP、托管 DevTools 和 Caddy/Authentik 入口。
- [moli-snap](https://github.com/sidalit/moli-snap) - 非官方 Snap 软件包，用于在 Linux 上运行 Moli CLI 和自动化服务。
- [orbsh/nixos](https://github.com/orbsh/nixos/blob/main/modules/system/units/moli.nix) - NixOS 软件包定义，固定 Moli 发布二进制及其运行时依赖。
- [Railway Moli](https://github.com/two-workspaces/moli) - Railway 部署模板，提供带令牌认证的 Caddy 网关与公共 WebSocket 地址改写。

<a id="experimental-and-development-examples"></a>

## 实验与开发案例

原型、开发脚本与评测报告。测试结果来自各项目作者。

- [Aveli](https://github.com/pkmdev-sec/aveli) - 面向浏览器 Agent 的实验性 Moli 运行时与兼容性探针。
- [govio-map](https://github.com/chenxinma/govio-map) - 通过 CDP 冒烟脚本检查应用设置对话框中的输入焦点与校验行为。
- [Hydra Downloader](https://github.com/juanpimg/hydradownloader) - 使用 Moli CDP 检查响应式布局和下载流程的开发脚本。
- [laravel-domains](https://github.com/yepbro/laravel-domains) - 爬虫项目，记录特定版本的 Moli 评测、回归问题、复测及 Chromium 对比。
- [llama.rs](https://github.com/yablokolabs/llama.rs) - 使用 Moli 检查 Rust/WASM 聊天应用 JavaScript 界面的浏览器测试脚本。
- [Master Maps](https://github.com/0bifthenelse/master-maps) - 地图应用，提供 Moli 端到端测试脚本及显式的本地 Chromium 回退。
- [Molifasi](https://github.com/A3S-Lab/Molifasi) - Rust 浏览器 Agent 原型，将 Moli CDP 观察与操作接入 Apofasi 决策。
- [ScopePay AI](https://github.com/yablokolabs/scopepay-ai) - PayPal 沙箱结账案例，使用 Moli CDP 执行买家审批流程。
- [SmartSpecPro](https://github.com/naibarn/SmartSpecPro) - 面向 Moli 的无 root Linux 验收测试启动器，不包含在默认构建中。

## 参与贡献

欢迎分享你的 Moli fork、二次开发项目和新用法，也欢迎改进已有条目。提交方式见[贡献指南](../CONTRIBUTING.md)。

## 附注

**2026-11-19** 核对了公开代码和项目文档。生产使用、客户关系及测试结果的独立复现情况仍未知。固定版本的源码链接、证据快照、历史提及与无法读取的仓库见[复核记录](REVIEW.md)。
