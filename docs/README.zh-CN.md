<h1 align="center">Awesome Moli</h1>

<p align="center">
  <a href="../README.md">English</a> | <strong>简体中文</strong> | <a href="README.ja.md">日本語</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.es.md">Español</a> | <a href="README.ko.md">한국어</a>
</p>

> [Moli](https://github.com/lexmount/moli) 是面向 AI Agent 的开源无头浏览器。这里收录使用、扩展或分发 Moli 的项目，包括浏览器自动化工具、框架集成、衍生项目、部署方案和开发案例。

## 目录

- [Fork 与衍生项目](#forks-and-derivatives)
- [测试与 QA 工具](#testing-and-qa-tools)
- [浏览器自动化与工作流](#browser-automation-and-workflows)
- [网页渲染与提取](#web-rendering-and-extraction)
- [Agent 框架与工作区](#agent-frameworks-and-workspaces)
- [打包与部署](#packaging-and-deployment)
- [开发案例与评测](#development-examples-and-evaluations)

<a id="forks-and-derivatives"></a>

## Fork 与衍生项目

- **[Limo](https://github.com/Spxg/limo) - 在终端用 Moli 的完整浏览器 Web API 运行 JavaScript。**
- [moli-stealth](https://github.com/Stravia-AI/moli-stealth) - 让 Moli 的 HTTP 和 WebSocket 连接使用 Chrome 风格的网络配置。
- [pilot](https://github.com/WSAdam/pilot) - 可开窗观看 Playwright MCP 驱动的 Agent 操作网页。

<a id="testing-and-qa"></a>
<a id="testing-and-qa-tools"></a>

## 测试与 QA 工具

- [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - 通过实验性 Moli 后端运行端到端测试。
- **[e2e](https://github.com/e2e-inc/e2e) - 用自然语言在 Moli 中测试结账等网页流程，回放已验证的操作时无需再调用模型。**
- [KMJ CodeBridge](https://github.com/kmjtechno/kmj-codebridge) - 可用 Moli 检查指定的公开测试页能否读出正文。

<a id="browser-tools-and-mcp"></a>
<a id="browser-automation-and-workflows"></a>

## 浏览器自动化与工作流

- [Browser Bridge for Muse](https://github.com/rehantheorylab-pixel/browser-bridge-for-muse) - Muse 可选用本地 Moli 进行 Playwright 自动化。
- [chatctl](https://github.com/ironpark/toolz/tree/main/cli/chatctl) - 在 Chrome 登录一次，就能用 Moli 从终端读取聊天记录。
- [Delta Browser](https://github.com/DevAnimecx/deltabrowser) - 在 x86_64 Linux 上用沙箱隔离 MCP 的 Moli 浏览会话。
- **[dsh-moli](https://github.com/27painter/dsh-moli) - DeepSeek Harness 社区插件，可把动态网页转成 Markdown。**
- [Moli Job Apply](https://github.com/mcaupybugs/claude-job-apply-skill-moli) - 实验性求职助手，填好申请表后等你确认再提交。

<a id="web-extraction-and-research"></a>
<a id="web-rendering-and-extraction"></a>

## 网页渲染与提取

- [888-url2md](https://github.com/tbdavid2019/888-url2md) - 批量把网页转成 Markdown，遇到动态页面就用 Moli 渲染。
- [A3S Search](https://github.com/A3S-Lab/Search) - 用 Moli 读取搜索结果中依赖 JavaScript 的网页。
- [Brains](https://github.com/YuniqueUnic/brains) - 可用 Moli 把动态网页存成带版本记录的 Markdown 笔记。
- **[CTI Expert](https://github.com/7onez/cti-expert) - 调查网络威胁时，用 Moli 读取网页动态加载的内容。**
- [HEIS](https://github.com/u4399com-beep/heis) - 可用 Moli 采集动态加载的网络小说章节。
- [hermes-dev](https://github.com/Sucotasch/hermes-dev) - Hermes Deep Research 读不到网页正文时，改用 Moli 渲染。
- [Lens](https://github.com/bysages/lens) - 通过 HTTP API 用 Moli 给网页截图。
- [ModalPrism](https://github.com/MistLoom/ModalPrism) - 用 Moli 渲染动态网页并存档，方便回看采集时的内容。
- [Moli Web Research](https://github.com/assistifyai405/moli-webonderzoek) - 本地 MCP 工具测试版，可对比网页在不同时间的快照。
- [molisnap](https://github.com/7a6163/molisnap) - 把单页应用预渲染成搜索爬虫和 AI 机器人能读取的 HTML。
- [PageSift](https://github.com/YOLOW92/pagesift) - 可选用 Moli 提取 Lightpanda 读不到的 iframe 内容。
- [Smart Tool](https://github.com/AllanSantos-DV/smart-tool-dist) - Windows 编码 Agent 用 HTTP 读不到正文时，可改用 Moli。
- [stvdy](https://github.com/jettapindika/stvdy) - Exa 取不到正文时，用 Moli 把网页导入为学习资料。
- [Vanilla](https://github.com/easylearnfromtw/vanilla) - 隔离出站网络后，可启用 Moli 导入公开网页正文。

<a id="agents-and-workspaces"></a>
<a id="agent-frameworks-and-workspaces"></a>

## Agent 框架与工作区

- [A3S Code](https://github.com/A3S-Lab/Code) - 为编码 Agent 的网页搜索自动配置经过校验的 Moli 浏览器。
- [agent-fabric](https://github.com/BlueTeam-OU/agent-fabric) - 每个编码 Agent 都有独立的临时 Moli 浏览会话。
- [agnostic-router-kit](https://github.com/adelvillar1/agnostic-router-kit) - 工作流需要读取 JavaScript 网页时，优先使用本地 Moli。
- [AION](https://github.com/JayCRL/AION) - 用 Moli 把动态网页整理成 Agent 工作区里的内容卡片。
- [dsh-qq-bot](https://github.com/arrow1031-dev/dsh-qq-bot) - QQ 机器人可用本地 Moli 把分享的网页转成 Markdown。
- [Internkim](https://github.com/yeomyeonggeori/internkim) - 让团队工作区里的 AI 助手用本地 Moli 浏览公开网页。
- [Lumen](https://github.com/Andrea17982/Lumen) - 让 Claude Code 和 Codex 等编码工具共用桌面端内置的 Moli。
- [mem0-omp](https://github.com/millianlmx/mem0-omp) - 让编码 Agent 凭令牌访问容器里的 Moli 浏览器。
- [Qianxun](https://github.com/imxood/qianxun) - 在 DeepSeek Harness 桌面工作台中检测本机 Moli 及其版本。
- [Relay](https://github.com/arcwright42/Relay) - 用 Moli 读取链接，即使页面超时也能发出提示词。
- [Wick](https://github.com/yogasw/wick) - Go Agent 可选用本地 Moli 把网页读成 Markdown。

<a id="deployment-and-packaging"></a>
<a id="packaging-and-deployment"></a>

## 打包与部署

社区维护的安装配方与部署模板。

- [1Panel App](https://github.com/skingko/1panel_app/tree/localApps/apps/x-moli) - 通过社区应用包在 1Panel 部署 Moli。
- [A3S CLI](https://github.com/A3S-Lab/CLI) - A3S 命令行工具随包提供对应平台的 Moli 运行时。
- [Homebrew Moli](https://github.com/hoishing/homebrew-moli) - 社区 Homebrew 源，可一起安装 Moli 和配套的官方 Agent 技能。
- [Lattice](https://github.com/mytecor/lattice/tree/main/profiles/moli) - 在 NixOS 上托管 Moli，可从远端用 DevTools 调试网页。
- [moli-snap](https://github.com/sidalit/moli-snap) - 非官方 Linux Snap 包，为 Moli 截图和 PDF 导出配好字体。
- [orbsh/nixos](https://github.com/orbsh/nixos/blob/main/modules/system/units/moli.nix) - 为 NixOS 固定 Moli 版本并校验安装包。
- [Railway Moli](https://github.com/two-workspaces/moli) - 在 Railway 上部署 Moli，用令牌控制远程浏览器访问。

<a id="experimental-and-development-examples"></a>
<a id="development-examples-and-evaluations"></a>

## 开发案例与评测

原型、开发脚本与评测报告。测试结果来自各项目作者。

- [Aveli](https://github.com/pkmdev-sec/aveli) - 提供实验性测试，检查浏览器 Agent 能否连上本地 Moli。
- [govio-map](https://github.com/chenxinma/govio-map) - 用 Moli 逐字输入，检查设置里的输入框会不会失焦。
- [Hydra Downloader](https://github.com/juanpimg/hydradownloader) - 用 Moli 检查下载页面在不同手机屏宽下是否溢出。
- [laravel-domains](https://github.com/yepbro/laravel-domains) - 对比爬虫在多个 Moli 版本和 Chromium 上的抓取结果。
- [llama.rs](https://github.com/yablokolabs/llama.rs) - 用 Moli 检查本地 WebAssembly 聊天演示能否回答问题。
- [Master Maps](https://github.com/0bifthenelse/master-maps) - 用 Moli 对 3D 地图做端到端测试，必要时回退到本地 Chromium。
- [Molifasi](https://github.com/A3S-Lab/Molifasi) - 浏览器 Agent 原型，由 Apofasi 选择动作，交给 Moli 执行。
- [ScopePay AI](https://github.com/yablokolabs/scopepay-ai) - 用 Moli 测试买家在 PayPal 沙箱结账时确认付款的流程。
- [SmartSpecPro](https://github.com/naibarn/SmartSpecPro) - 仅在 Linux 验收测试中以普通用户权限启动 Moli。

## 参与贡献

欢迎分享你的 Moli fork、二次开发项目和新用法，也欢迎改进已有条目。提交方式见[贡献指南](../CONTRIBUTING.md)。

## 附注

**2026-11-19** 核对了公开代码和项目文档。生产使用、客户关系及测试结果的独立复现情况仍未知。固定版本的源码链接、证据快照、历史提及与无法读取的仓库见[复核记录](REVIEW.md)。
