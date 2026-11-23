<h1 align="center">Awesome Moli</h1>

<p align="center">
  <strong>English</strong> | <a href="docs/README.zh-CN.md">简体中文</a> | <a href="docs/README.ja.md">日本語</a> | <a href="docs/README.de.md">Deutsch</a> | <a href="docs/README.fr.md">Français</a> | <a href="docs/README.es.md">Español</a> | <a href="docs/README.ko.md">한국어</a>
</p>

> [Moli](https://github.com/lexmount/moli) is an open-source headless browser for AI agents. This list covers projects that use, extend, or distribute Moli, including browser automation tools, framework integrations, forks, deployment options, and development examples.

## Contents

- [Forks and derivatives](#forks-and-derivatives)
- [Testing and QA tools](#testing-and-qa-tools)
- [Browser automation and workflows](#browser-automation-and-workflows)
- [Web rendering and extraction](#web-rendering-and-extraction)
- [Agent frameworks and workspaces](#agent-frameworks-and-workspaces)
- [Packaging and deployment](#packaging-and-deployment)
- [Development examples and evaluations](#development-examples-and-evaluations)

## Forks and derivatives

- **[Limo](https://github.com/Spxg/limo) - Runs JavaScript in the terminal with all of Moli’s browser Web APIs.**
- [moli-stealth](https://github.com/Stravia-AI/moli-stealth) - Gives Moli’s HTTP and WebSocket connections a Chrome-like network profile.
- [pilot](https://github.com/WSAdam/pilot) - Can open a window to watch a Playwright MCP agent browse.

<a id="testing-and-qa"></a>

## Testing and QA tools

- [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - Runs end-to-end tests with Moli through an experimental backend.
- **[e2e](https://github.com/e2e-inc/e2e) - Tests web flows like checkout in Moli using plain language and replays verified actions without another model call.**
- [KMJ CodeBridge](https://github.com/kmjtechno/kmj-codebridge) - Can check whether Moli extracts text from predefined public test pages.

<a id="browser-tools-and-mcp"></a>

## Browser automation and workflows

- [Browser Bridge for Muse](https://github.com/rehantheorylab-pixel/browser-bridge-for-muse) - Offers local Moli as a Playwright browser for Muse.
- [chatctl](https://github.com/ironpark/toolz/tree/main/cli/chatctl) - Reuses your Chrome login to read chats in the terminal with Moli.
- [Delta Browser](https://github.com/DevAnimecx/deltabrowser) - Runs MCP browser sessions in sandboxed Moli workers on x86_64 Linux.
- **[dsh-moli](https://github.com/27painter/dsh-moli) - Cross-agent browser tools for DeepSeek Harness, Codex, and OpenCode, built on a separately installed Moli engine.**
- [Moli Job Apply](https://github.com/mcaupybugs/claude-job-apply-skill-moli) - An experimental assistant that fills out job applications and asks before submitting.
- [sessfork](https://github.com/wasabihu/sessfork) - On macOS and Linux, AI agents can use Moli in the background to browse sites you’re signed into in Chrome.

<a id="web-extraction-and-research"></a>

## Web rendering and extraction

- [888-url2md](https://github.com/tbdavid2019/888-url2md) - Batch-converts webpages to Markdown, rendering JavaScript pages with Moli.
- [A3S Search](https://github.com/A3S-Lab/Search) - Reads JavaScript-heavy pages from search results with Moli.
- [Brains](https://github.com/YuniqueUnic/brains) - Can save dynamic webpages as versioned Markdown notes with Moli.
- **[CTI Expert](https://github.com/7onez/cti-expert) - Reads JavaScript-rendered pages with Moli for threat investigations. [Install Moli (§4)](https://github.com/7onez/cti-expert/blob/main/scripts/platform-setup.md#4-fastest-path--run-the-bundled-installer-once)**
- [HEIS](https://github.com/u4399com-beep/heis) - Can collect dynamically loaded web novel chapters with Moli.
- [hermes-dev](https://github.com/Sucotasch/hermes-dev#4-deepseek-harness-bridge-agents-own-web-tooling) - `mfetch` calls Moli directly to read pages as Markdown, `render` uses it when a page needs a browser, and both can fall back to HTTP.
- [Lens](https://github.com/bysages/lens) - Takes webpage screenshots with Moli through an HTTP API.
- [ModalPrism](https://github.com/MistLoom/ModalPrism) - Archives Moli-rendered pages as they appeared at collection time.
- [Moli Web Research](https://github.com/assistifyai405/moli-webonderzoek) - A local MCP tool in beta that compares saved webpage snapshots.
- [molisnap](https://github.com/7a6163/molisnap) - Prerenders single-page apps as HTML that search crawlers and AI bots can read.
- [PageSift](https://github.com/YOLOW92/pagesift) - Offers Moli as a fallback for iframe content Lightpanda misses.
- [Smart Tool](https://github.com/AllanSantos-DV/smart-tool-dist) - Lets Windows coding agents read pages with Moli when HTTP alone falls short.
- [stvdy](https://github.com/jettapindika/stvdy) - Saves webpages as study materials with Moli when Exa misses the text.
- [Vanilla](https://github.com/easylearnfromtw/vanilla) - Offers opt-in Moli imports of public webpages once outbound traffic is isolated.

<a id="agents-and-workspaces"></a>

## Agent frameworks and workspaces

- [A3S Code](https://github.com/A3S-Lab/Code) - Automatically sets up a verified Moli browser for coding agents’ web searches.
- [agent-fabric](https://github.com/BlueTeam-OU/agent-fabric) - Gives each coding agent its own temporary Moli browser session.
- [agnostic-router-kit](https://github.com/adelvillar1/agnostic-router-kit) - Uses local Moli first when workflows need JavaScript-rendered pages.
- [AION](https://github.com/JayCRL/AION) - Displays Moli-rendered pages as cards in the agent’s workspace.
- [dsh-qq-bot](https://github.com/arrow1031-dev/dsh-qq-bot) - A QQ bot that can use local Moli to read shared links as Markdown.
- [Internkim](https://github.com/yeomyeonggeori/internkim) - Lets a team’s AI assistant browse public pages with local Moli.
- [Lumen](https://github.com/Andrea17982/Lumen) - Lets desktop agents like Claude Code and Codex share a bundled Moli browser tool.
- [mem0-omp](https://github.com/millianlmx/mem0-omp) - Connects coding agents to a containerized Moli browser using a token.
- [Qianxun](https://github.com/imxood/qianxun) - Detects the local Moli version in a DeepSeek Harness desktop app.
- [Relay](https://github.com/arcwright42/Relay) - Lets you send a prompt even when a Moli page fetch times out.
- [Wick](https://github.com/yogasw/wick) - Gives Go agents the option to read webpages as Markdown with local Moli.

<a id="deployment-and-packaging"></a>

## Packaging and deployment

Community installation recipes and deployment templates.

- [1Panel App](https://github.com/skingko/1panel_app/tree/localApps/apps/x-moli) - A community package for deploying Moli through 1Panel.
- [A3S CLI](https://github.com/A3S-Lab/CLI) - Ships the platform-specific Moli runtime with the A3S CLI.
- [Homebrew Moli](https://github.com/hoishing/homebrew-moli) - A community Homebrew tap for installing Moli and its matching official agent skills.
- [Lattice](https://github.com/mytecor/lattice/tree/main/profiles/moli) - Hosts Moli on NixOS for remote debugging with DevTools.
- [moli-snap](https://github.com/sidalit/moli-snap) - An unofficial Linux Snap bundling Moli with fonts for screenshots and PDFs.
- [orbsh/nixos](https://github.com/orbsh/nixos/blob/main/modules/system/units/moli.nix) - Pins the Moli binary by version and checksum on NixOS.
- [Railway Moli](https://railway.com/deploy/moli?referralCode=sLjDXb) - Deploys a token-protected Moli browser on Railway.

<a id="experimental-and-development-examples"></a>

## Development examples and evaluations

Prototypes, development scripts, and evaluation reports. Reported test outcomes belong to their authors.

- [Aveli](https://github.com/pkmdev-sec/aveli) - An experimental check that connects the browser agent to local Moli.
- [govio-map](https://github.com/chenxinma/govio-map) - Uses Moli to check that a settings field keeps focus while typing.
- [Hydra Downloader](https://github.com/juanpimg/hydradownloader) - Checks the download page for overflow at different phone widths with Moli.
- [laravel-domains](https://github.com/yepbro/laravel-domains) - Compares its crawler across Moli versions and against Chromium.
- [llama.rs](https://github.com/yablokolabs/llama.rs) - Tests whether its local WebAssembly chat demo answers a question in Moli.
- [Master Maps](https://github.com/0bifthenelse/master-maps) - Runs end-to-end tests on its 3D map with Moli or local Chromium as a fallback.
- [Molifasi](https://github.com/A3S-Lab/Molifasi) - A prototype agent where Apofasi chooses actions and Moli performs them.
- [ScopePay AI](https://github.com/yablokolabs/scopepay-ai) - Tests buyer approval with Moli in PayPal’s sandbox checkout.
- [SmartSpecPro](https://github.com/naibarn/SmartSpecPro) - Launches Moli only for Linux acceptance tests without root privileges.

## Contributing

We welcome Moli forks, derivatives, and new uses. To share a project or improve an entry, see the [contribution guidelines](CONTRIBUTING.md).

## Footnotes

The initial source review took place on **2026-11-19**. Production use, customer relationships, and test results were outside the scope of this source review. The [review log](docs/REVIEW.md) links to pinned sources, evidence snapshots, and notes on historical or unavailable projects.
