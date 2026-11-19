# Awesome Moli [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
  <strong>English</strong> | <a href="docs/README.zh-CN.md">简体中文</a> | <a href="docs/README.ja.md">日本語</a> | <a href="docs/README.de.md">Deutsch</a> | <a href="docs/README.fr.md">Français</a> | <a href="docs/README.es.md">Español</a> | <a href="docs/README.ko.md">한국어</a>
</p>

> Tools, integrations, and examples for [Moli](https://github.com/lexmount/moli), the open-source headless browser for AI agents.

Explore ways to use Moli for browser automation, web extraction, agent workflows, and self-hosted services. Some integrations are optional or experimental; follow each project's setup guide.

## Contents

- [Official resources](#official-resources)
- [Forks and derivatives](#forks-and-derivatives)
- [Browser tools and MCP](#browser-tools-and-mcp)
- [Agents and workspaces](#agents-and-workspaces)
- [Web extraction and research](#web-extraction-and-research)
- [Testing and QA](#testing-and-qa)
- [Deployment and packaging](#deployment-and-packaging)
- [Experimental and development examples](#experimental-and-development-examples)

## Official resources

- [Moli](https://github.com/lexmount/moli) - Official repository, installation instructions, CLI usage, and automation protocol documentation.
- [Releases](https://github.com/lexmount/moli/releases) - Prebuilt binaries and upstream release notes.
- [Agent skills](https://github.com/lexmount/moli/tree/main/skills) - Official agent skills for page fetching, web search, and running a CDP server.
- [WebMCP playground](https://github.com/lexmount/moli/tree/main/moli-playground/webmcp) - Scripts and demos for discovering and calling a site's native WebMCP tools through Moli.
- [Webstone](https://github.com/lexmount/webstone) - Browser and web-tool evaluation harness with reproducible tasks and recorded evidence.

## Forks and derivatives

- [moli-stealth](https://github.com/Stravia-AI/moli-stealth) - Moli fork with a Chrome-style network profile and a shared Rust transport for HTTP and WebSockets.
- [pilot](https://github.com/WSAdam/pilot) - Moli-derived browser that Playwright and Playwright MCP can launch directly, with an optional window for watching the agent browse. [Playwright setup](https://github.com/WSAdam/pilot/blob/main/pilot/README.md)

## Browser tools and MCP

- [Browser Bridge for Muse](https://github.com/rehantheorylab-pixel/browser-bridge-for-muse) - Browser automation bridge with an optional Moli backend driven through Playwright over CDP.
- [chatctl](https://github.com/ironpark/toolz/tree/main/cli/chatctl) - Go CLI for managing chat web sessions, with Moli for headless access and Chrome for interactive login.
- [Delta Browser](https://github.com/DevAnimecx/deltabrowser) - MCP browser server with a managed Moli engine and sandboxed workers on Linux x86_64.
- [dsh-moli](https://github.com/27painter/dsh-moli) - DeepSeek Harness community plugin for page extraction, JavaScript evaluation, screenshots, PDFs, and engine diagnostics.
- [Limo](https://github.com/Spxg/limo) - Command-line JavaScript runner that embeds `moli-core` from Spxg’s Moli fork, giving scripts access to the DOM and browser events.
- [Moli Job Apply](https://github.com/mcaupybugs/claude-job-apply-skill-moli) - Experimental job-search skill that fills application forms through Moli and requires confirmation before submission.
- [Moli Web Research](https://github.com/assistifyai405/moli-webonderzoek) - Local MCP research tools for reading selected URLs, retaining source evidence, and comparing page snapshots; currently in beta.
- [Smart Tool](https://github.com/AllanSantos-DV/smart-tool-dist) - Windows agent-tool distribution that uses Moli for JavaScript pages when HTTP extraction falls short, with Chromium fallback.

## Agents and workspaces

- [A3S Code](https://github.com/A3S-Lab/Code) - Agent framework that provisions a verified Moli runtime for its headless web-search backend.
- [agent-fabric](https://github.com/BlueTeam-OU/agent-fabric) - Coding-agent control plane using Moli for web reading and per-agent scripted browsing through Playwright MCP.
- [agnostic-router-kit](https://github.com/adelvillar1/agnostic-router-kit) - Agent workflow toolkit with Moli-first page rendering, followed by self-hosted Firecrawl and plain HTTP fallbacks.
- [AION](https://github.com/JayCRL/AION) - Agent infrastructure whose web.read tool uses Moli to return rendered Markdown or structured DOM data.
- [dsh-qq-bot](https://github.com/arrow1031-dev/dsh-qq-bot) - QQ bot integration with an optional local Moli rendering path for its qq_webfetch tool.
- [Internkim](https://github.com/yeomyeonggeori/internkim) - Team agent workspace with a Moli browser runtime for public-page navigation.
- [Lumen](https://github.com/Andrea17982/Lumen) - Desktop agent workspace that bundles Moli and shares browser tools across multiple model and CLI adapters.
- [mem0-omp](https://github.com/millianlmx/mem0-omp) - Coding-agent harness with containerized Moli browsers and an authenticated HTTP/WebSocket CDP gateway.
- [Qianxun](https://github.com/imxood/qianxun) - Tauri desktop workbench for DeepSeek Harness with local Moli executable discovery and version checks.
- [Relay](https://github.com/arcwright42/Relay) - Agent runtime with bounded Moli page fetches and managed browser installation.
- [Wick](https://github.com/yogasw/wick) - Go agent host with an optional Moli browser connector, CDP sessions, and Markdown extraction.

## Web extraction and research

- [888-url2md](https://github.com/tbdavid2019/888-url2md) - Page-to-Markdown service with a local Moli CDP backend and a separate Chrome fallback policy.
- [A3S Search](https://github.com/A3S-Lab/Search) - Embeddable search engine with a Moli CLI renderer and bounded rendering concurrency.
- [Brains](https://github.com/YuniqueUnic/brains) - Versioned Markdown knowledge store with optional Moli rendering when importing URLs.
- [CTI Expert](https://github.com/7onez/cti-expert) - Threat-intelligence toolkit using Moli for JavaScript-rendered DOM extraction, with Chromium retained for visual evidence.
- [HEIS](https://github.com/u4399com-beep/heis) - Novel collection system with a Go HTTP bridge around Moli fetch and script evaluation.
- [hermes-dev](https://github.com/Sucotasch/hermes-dev) - Hermes research tools with Moli rendering as an additional step in the page-reading fallback chain.
- [Lens](https://github.com/bysages/lens) - TypeScript web toolkit using Moli over CDP for screenshots and page reading.
- [ModalPrism](https://github.com/MistLoom/ModalPrism) - Rust data-collection system whose browser accessor renders dynamic pages through the Moli CLI.
- [molisnap](https://github.com/7a6163/molisnap) - SPA prerendering service for search crawlers and AI bots, with caching and sitemap prewarming.
- [PageSift](https://github.com/YOLOW92/pagesift) - Rust web and document extraction service with Moli in a Lightpanda–Moli–Chrome browser selection chain.
- [stvdy](https://github.com/jettapindika/stvdy) - Study workspace that imports web sources through an Exa, Moli, and HTTP/readability fallback chain.
- [Vanilla](https://github.com/easylearnfromtw/vanilla) - Family AI workspace with an opt-in Moli page-extraction adapter that requires separately configured outbound network isolation.

## Testing and QA

- [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - End-to-end testing framework with an experimental Moli helper supporting local process management and existing CDP endpoints.
- [KMJ CodeBridge](https://github.com/kmjtechno/kmj-codebridge) - MCP development toolkit with optional Moli extraction checks for fixed public pages and Chrome visual-QA fallback.

## Deployment and packaging

Community installation recipes and deployment templates.

- [1Panel App](https://github.com/skingko/1panel_app/tree/localApps/apps/x-moli) - Community 1Panel application recipe and Docker image build for Moli.
- [A3S CLI](https://github.com/A3S-Lab/CLI) - A3S command-line distribution with a bundled, target-specific Moli runtime.
- [Homebrew Moli](https://github.com/hoishing/homebrew-moli) - Community Homebrew tap installing Moli binaries and the corresponding official agent skills.
- [Lattice](https://github.com/mytecor/lattice/tree/main/profiles/moli) - NixOS Moli service with remote CDP access, hosted DevTools, and Caddy/Authentik ingress.
- [moli-snap](https://github.com/sidalit/moli-snap) - Unofficial Snap package for running the Moli CLI and automation server on Linux.
- [orbsh/nixos](https://github.com/orbsh/nixos/blob/main/modules/system/units/moli.nix) - NixOS package definition for pinned Moli release binaries and their runtime dependencies.
- [Railway Moli](https://github.com/two-workspaces/moli) - Railway deployment template with a token-protected Caddy gateway and public WebSocket endpoint rewriting.

## Experimental and development examples

Prototypes, development scripts, and evaluation reports. Reported test outcomes belong to their authors.

- [Aveli](https://github.com/pkmdev-sec/aveli) - Experimental Moli runtime and compatibility probes for a browser agent.
- [govio-map](https://github.com/chenxinma/govio-map) - CDP smoke script checking input focus and validation in an application's settings dialog.
- [Hydra Downloader](https://github.com/juanpimg/hydradownloader) - Development scripts using Moli CDP to check responsive layout and download workflows.
- [laravel-domains](https://github.com/yepbro/laravel-domains) - Crawler project documenting version-specific Moli evaluations, regressions, retests, and Chromium comparisons.
- [llama.rs](https://github.com/yablokolabs/llama.rs) - Browser test script using Moli to exercise a Rust/WASM chat application's JavaScript interface.
- [Master Maps](https://github.com/0bifthenelse/master-maps) - Map application with Moli-driven end-to-end scripts and an explicit local Chromium fallback.
- [Molifasi](https://github.com/A3S-Lab/Molifasi) - Rust browser-agent prototype combining Moli CDP observations and actions with Apofasi decisions.
- [ScopePay AI](https://github.com/yablokolabs/scopepay-ai) - PayPal sandbox checkout example using Moli CDP for the buyer approval flow.
- [SmartSpecPro](https://github.com/naibarn/SmartSpecPro) - Rootless Linux acceptance-test launcher for Moli, excluded from default builds.

## Contributing

We welcome Moli forks, derivatives, and new uses. To share a project or improve an entry, see the [contribution guidelines](CONTRIBUTING.md).

## Footnotes

Sources were reviewed on **2026-11-19**. Production use, customer relationships, and test results were outside the scope of this source review. The [review log](docs/REVIEW.md) links to pinned sources, evidence snapshots, and notes on historical or unavailable projects.
