# Source review — 2026-11-19

The initial review covered **55 named repositories** from the supplied research, including 52 main-list entries and three backlog additions. Later reviews covered three suggested forks and downstream projects, then the e2e testing framework. The complete dataset behind the original 185 historical records was unavailable.

All seven language editions list the same **52 projects** under Integrations and Community projects. Of the **59 repositories reviewed**, seven are held for further evidence.

## Method

- Retrieved repository metadata to resolve names, stable repository IDs, and default branches.
- Used GitHub code search to locate Moli references. Empty or rate-limited searches were followed by file-tree inspection and targeted source or documentation reads.
- Read sources at a fixed commit and recorded repository IDs, paths, blob SHAs, and retrieval times. [Initial 55 repositories](../data/review-2026-11-19.json) · [Three forks and downstream projects](../data/review-2026-11-19-additions.json) · [e2e framework adapter](../data/review-2026-11-19-e2e.json)
- Kept optional backends, packaging, prototypes, and development tests distinct. No stars, forks, downloads, or author-reported performance claims are used to rank entries.
- Performed a static review. No third-party project was installed or executed; CI, benchmarks, production deployments, active users, and payments were not independently verified.

The commit timestamp is not an adoption date. A repository returning 404 may have been renamed, made private, removed, or become inaccessible to the reader. Cached search pages cannot establish its current state.

## Included projects

Each source link below points to the exact commit reviewed. Repository names and section labels match the README; the renamed Muse bridge is listed only once.

| Project | README section | Primary source |
| --- | --- | --- |
| [codeceptjs/CodeceptJS](https://github.com/codeceptjs/CodeceptJS) | Testing and QA | [docs/helpers/Moli.md](https://github.com/codeceptjs/CodeceptJS/blob/402fbb9d4bd4c033f8bf6642bc0362261706c356/docs/helpers/Moli.md) |
| [e2e-inc/e2e](https://github.com/e2e-inc/e2e) | Testing and QA | [Moli provider](https://github.com/e2e-inc/e2e/blob/402a6157ce4b61c6f4d173b0c1c4f6361bea0634/packages/moli/src/provider.ts#L22-L50) · [Merged PR #1843](https://github.com/e2e-inc/e2e/pull/1843) |
| [kmjtechno/kmj-codebridge](https://github.com/kmjtechno/kmj-codebridge) | Testing and QA | [scripts/browser-moli-fast.mjs](https://github.com/kmjtechno/kmj-codebridge/blob/d5c06c2028f90ec14734cef712fe86c6db298e66/scripts/browser-moli-fast.mjs) |
| [rehantheorylab-pixel/browser-bridge-for-muse](https://github.com/rehantheorylab-pixel/browser-bridge-for-muse) | Browser tools and MCP | [core/backends/moli_backend.py](https://github.com/rehantheorylab-pixel/browser-bridge-for-muse/blob/aeb5a3bddc8fd0fbba01930e451a7ef6044d00c5/core/backends/moli_backend.py) |
| [ironpark/toolz](https://github.com/ironpark/toolz) | Browser tools and MCP | [cli/chatctl/README.md](https://github.com/ironpark/toolz/blob/ce825adf74e2b078b2eff4394deb97c70d341aef/cli/chatctl/README.md) |
| [DevAnimecx/deltabrowser](https://github.com/DevAnimecx/deltabrowser) | Browser tools and MCP | [README.md](https://github.com/DevAnimecx/deltabrowser/blob/ecd9780fcf89012314bc1102763179c270024256/README.md) |
| [27painter/dsh-moli](https://github.com/27painter/dsh-moli) | Browser tools and MCP | [README.md](https://github.com/27painter/dsh-moli/blob/56a28721fc2977f450d3ada9f03acad50e9b97d4/README.md) |
| [mcaupybugs/claude-job-apply-skill-moli](https://github.com/mcaupybugs/claude-job-apply-skill-moli) | Browser tools and MCP | [README.md](https://github.com/mcaupybugs/claude-job-apply-skill-moli/blob/4b04e9e4b8a2b912a6a1a6c2594c2c6edb2b9e0f/README.md) |
| [assistifyai405/moli-webonderzoek](https://github.com/assistifyai405/moli-webonderzoek) | Browser tools and MCP | [README.md](https://github.com/assistifyai405/moli-webonderzoek/blob/d7a218c60bc298a08f167198d6ffa3df09483ae5/README.md) |
| [AllanSantos-DV/smart-tool-dist](https://github.com/AllanSantos-DV/smart-tool-dist) | Browser tools and MCP | [smart_tool_daemon.py](https://github.com/AllanSantos-DV/smart-tool-dist/blob/04f1ca4e8e0c07048aad2c43f31d218df4c1accf/smart_tool_daemon.py) |
| [A3S-Lab/Code](https://github.com/A3S-Lab/Code) | Agents and workspaces | [core/src/moli_runtime.rs](https://github.com/A3S-Lab/Code/blob/cfaa22e8f1fca7ad1bfe132ac97ce7be930071f2/core/src/moli_runtime.rs) |
| [BlueTeam-OU/agent-fabric](https://github.com/BlueTeam-OU/agent-fabric) | Agents and workspaces | [docs/moli.md](https://github.com/BlueTeam-OU/agent-fabric/blob/2629b3378c2fffbcfb43f65920f352cb5272453f/docs/moli.md) |
| [adelvillar1/agnostic-router-kit](https://github.com/adelvillar1/agnostic-router-kit) | Agents and workspaces | [docs/features/browsing.md](https://github.com/adelvillar1/agnostic-router-kit/blob/7fd0aace60231a290a471e89d5b2e4d19afd9eca/docs/features/browsing.md) |
| [JayCRL/AION](https://github.com/JayCRL/AION) | Agents and workspaces | [crates/aion-services/src/tool/web.rs](https://github.com/JayCRL/AION/blob/6256b74992964f398c5fa946a5db442a13ab4e2f/crates/aion-services/src/tool/web.rs) |
| [arrow1031-dev/dsh-qq-bot](https://github.com/arrow1031-dev/dsh-qq-bot) | Agents and workspaces | [lib/tools/moli.js](https://github.com/arrow1031-dev/dsh-qq-bot/blob/3cf89268312a084160a2fb314c674a220b43ba29/lib/tools/moli.js) |
| [yeomyeonggeori/internkim](https://github.com/yeomyeonggeori/internkim) | Agents and workspaces | [internal/browser/runtime.go](https://github.com/yeomyeonggeori/internkim/blob/82bccd8ea7e995317f221029396b1b5d61880800/internal/browser/runtime.go) |
| [Andrea17982/Lumen](https://github.com/Andrea17982/Lumen) | Agents and workspaces | [docs/moli.md](https://github.com/Andrea17982/Lumen/blob/e940abe724ecdc7e61467cb926c2f2ec1da3d1f1/docs/moli.md) |
| [millianlmx/mem0-omp](https://github.com/millianlmx/mem0-omp) | Agents and workspaces | [omp-harness/deploy/container/moli-gate.ts](https://github.com/millianlmx/mem0-omp/blob/a38e5d702b9687034f68840f7be5e9e98d3cb4b0/omp-harness/deploy/container/moli-gate.ts) |
| [imxood/qianxun](https://github.com/imxood/qianxun) | Agents and workspaces | [src-tauri/src/tools/moli.rs](https://github.com/imxood/qianxun/blob/61b7158c6b63576df1ac58f4f72c66a91602522f/src-tauri/src/tools/moli.rs) |
| [arcwright42/Relay](https://github.com/arcwright42/Relay) | Agents and workspaces | [crates/relay-runtime/src/webfetch.rs](https://github.com/arcwright42/Relay/blob/62fd54ad3af8bde025d6e24e7b9733c439cc3cb8/crates/relay-runtime/src/webfetch.rs) |
| [yogasw/wick](https://github.com/yogasw/wick) | Agents and workspaces | [plugins/connector/playwright_browser/moli.go](https://github.com/yogasw/wick/blob/b8738a7331c9c2d9b6fca3ae32a72dba373f8949/plugins/connector/playwright_browser/moli.go) |
| [tbdavid2019/888-url2md](https://github.com/tbdavid2019/888-url2md) | Web extraction and research | [src/services/moli-browser.ts](https://github.com/tbdavid2019/888-url2md/blob/e72d5fb45ec3658cfebb96ee6f476528f5f5375b/src/services/moli-browser.ts) |
| [A3S-Lab/Search](https://github.com/A3S-Lab/Search) | Web extraction and research | [src/moli.rs](https://github.com/A3S-Lab/Search/blob/e09b62b9e918875315c3cd3c7e14b5a9f9180367/src/moli.rs) |
| [YuniqueUnic/brains](https://github.com/YuniqueUnic/brains) | Web extraction and research | [crates/client/src/url_import.rs](https://github.com/YuniqueUnic/brains/blob/84eb0cf863dd1947913034614596b24f5f34268e/crates/client/src/url_import.rs) |
| [7onez/cti-expert](https://github.com/7onez/cti-expert) | Web extraction and research | [intel_engine/WebPivot/tools/wp_moli.py](https://github.com/7onez/cti-expert/blob/407b444b899c4bf54cb38e4b85fe42821c7f157d/intel_engine/WebPivot/tools/wp_moli.py) |
| [u4399com-beep/heis](https://github.com/u4399com-beep/heis) | Web extraction and research | [go-backend/services/moli-bridge/main.go](https://github.com/u4399com-beep/heis/blob/cf6e46b0f575dc979ac07bd5740230cacead0346/go-backend/services/moli-bridge/main.go) |
| [Sucotasch/hermes-dev](https://github.com/Sucotasch/hermes-dev) | Web extraction and research | [webtools_bridge.py](https://github.com/Sucotasch/hermes-dev/blob/19b7c4323d1ce2ad1e6652d60283a86cd8f1d666/webtools_bridge.py) |
| [bysages/lens](https://github.com/bysages/lens) | Web extraction and research | [README.md](https://github.com/bysages/lens/blob/0ac9760c188575c8d156881745cac537e339b5a4/README.md) |
| [MistLoom/ModalPrism](https://github.com/MistLoom/ModalPrism) | Web extraction and research | [apps/modalprism-collector/subsystems/accessors-builtin/src/browser.rs](https://github.com/MistLoom/ModalPrism/blob/cfd53efca298db1bc9ab002b53aa8a1c1f832421/apps/modalprism-collector/subsystems/accessors-builtin/src/browser.rs) |
| [7a6163/molisnap](https://github.com/7a6163/molisnap) | Web extraction and research | [src/render.rs](https://github.com/7a6163/molisnap/blob/6c2c305038adf283da2efdce360d9b25ec762866/src/render.rs) |
| [YOLOW92/pagesift](https://github.com/YOLOW92/pagesift) | Web extraction and research | [crates/pagesift-cdp/src/engine.rs](https://github.com/YOLOW92/pagesift/blob/6aebf81523233b6ccc402546f0669ca1719d11d9/crates/pagesift-cdp/src/engine.rs) |
| [jettapindika/stvdy](https://github.com/jettapindika/stvdy) | Web extraction and research | [crates/server/src/integrations/fetch.rs](https://github.com/jettapindika/stvdy/blob/4692865b0e4d21bdada2c6270715290c6c49d52a/crates/server/src/integrations/fetch.rs) |
| [easylearnfromtw/vanilla](https://github.com/easylearnfromtw/vanilla) | Web extraction and research | [services/weiguo/moli_engine.py](https://github.com/easylearnfromtw/vanilla/blob/d344aa51a664ab685892493794f921d99f97970e/services/weiguo/moli_engine.py) |
| [Spxg/limo](https://github.com/Spxg/limo) | Forks and derivatives | [Terminal Web APIs and DOM example](https://github.com/Spxg/limo/blob/73519b9ab71904c670917a93fcd54e756c69c570/README.md#L1-L42) |
| [Stravia-AI/moli-stealth](https://github.com/Stravia-AI/moli-stealth) | Forks and derivatives | [Network transport](https://github.com/Stravia-AI/moli-stealth/blob/65b76086fe98b890bbd4755899698c71bdcef1d7/README.md#L137-L144) · [Fetch dependency](https://github.com/Stravia-AI/moli-stealth/blob/65b76086fe98b890bbd4755899698c71bdcef1d7/moli-fetch/Cargo.toml#L21) |
| [WSAdam/pilot](https://github.com/WSAdam/pilot) | Forks and derivatives | [Fork history](https://github.com/WSAdam/pilot/blob/6db71df64b45f7652dc4e999aa900dd8b74ba719/FORK.md#L1-L12) · [Playwright and window guide](https://github.com/WSAdam/pilot/blob/6db71df64b45f7652dc4e999aa900dd8b74ba719/pilot/README.md) |
| [skingko/1panel_app](https://github.com/skingko/1panel_app) | Deployment and packaging | [apps/x-moli/README.md](https://github.com/skingko/1panel_app/blob/136be7b158e50a884334835770ce8a445761270e/apps/x-moli/README.md) |
| [A3S-Lab/CLI](https://github.com/A3S-Lab/CLI) | Deployment and packaging | [README.md](https://github.com/A3S-Lab/CLI/blob/d9287345624a2e71e6614268bec1563ac65a9a28/README.md) |
| [hoishing/homebrew-moli](https://github.com/hoishing/homebrew-moli) | Deployment and packaging | [README.md](https://github.com/hoishing/homebrew-moli/blob/282b619f499adee0efba4f9c02b2d2d70a4de1f5/README.md) |
| [mytecor/lattice](https://github.com/mytecor/lattice) | Deployment and packaging | [profiles/moli/README.md](https://github.com/mytecor/lattice/blob/d201e63693794feacffb497c090ac4725ae66abc/profiles/moli/README.md) |
| [sidalit/moli-snap](https://github.com/sidalit/moli-snap) | Deployment and packaging | [README.md](https://github.com/sidalit/moli-snap/blob/7766861a7749ada2196c51cc762836ee56c00eed/README.md) |
| [orbsh/nixos](https://github.com/orbsh/nixos) | Deployment and packaging | [modules/system/units/moli.nix](https://github.com/orbsh/nixos/blob/4d507d573270264ea35388eb0394646fc343af7c/modules/system/units/moli.nix) |
| [two-workspaces/moli](https://github.com/two-workspaces/moli) | Deployment and packaging | [README.md](https://github.com/two-workspaces/moli/blob/31839d12461a2d8403b81ff0d3bad75bf3f35019/README.md) |
| [pkmdev-sec/aveli](https://github.com/pkmdev-sec/aveli) | Experimental and development examples | [aveli/moli.py](https://github.com/pkmdev-sec/aveli/blob/8c59e1d516cd7e0a42b332c105596fe189fd4e27/aveli/moli.py) |
| [chenxinma/govio-map](https://github.com/chenxinma/govio-map) | Experimental and development examples | [docs/tasks/X11-settings-provider-name-input/smoke-browser-cdp.mjs](https://github.com/chenxinma/govio-map/blob/112df85b80b091be7faf867009691f7519833656/docs/tasks/X11-settings-provider-name-input/smoke-browser-cdp.mjs) |
| [juanpimg/hydradownloader](https://github.com/juanpimg/hydradownloader) | Experimental and development examples | [scripts/verify-responsive-moli.mjs](https://github.com/juanpimg/hydradownloader/blob/6d369c6c0c7aa755c17fcda55f2847684e09c4c6/scripts/verify-responsive-moli.mjs) |
| [yepbro/laravel-domains](https://github.com/yepbro/laravel-domains) | Experimental and development examples | [docs/questions/moli-render-engine.md](https://github.com/yepbro/laravel-domains/blob/63f46edf7c62ed2ace6304a4fa0e81272e13f1b0/docs/questions/moli-render-engine.md) |
| [yablokolabs/llama.rs](https://github.com/yablokolabs/llama.rs) | Experimental and development examples | [scripts/browser_test.sh](https://github.com/yablokolabs/llama.rs/blob/d01d378b7003619c7c19ae712b337b27722f6bf3/scripts/browser_test.sh) |
| [0bifthenelse/master-maps](https://github.com/0bifthenelse/master-maps) | Experimental and development examples | [scripts/moli/run-e2e.ts](https://github.com/0bifthenelse/master-maps/blob/a955c5eef0f36f48c0b16e79939a5eb2354e4712/scripts/moli/run-e2e.ts) |
| [A3S-Lab/Molifasi](https://github.com/A3S-Lab/Molifasi) | Experimental and development examples | [README.md](https://github.com/A3S-Lab/Molifasi/blob/eac3ab32b310047fa89b44aedbac476cf004446e/README.md) |
| [yablokolabs/scopepay-ai](https://github.com/yablokolabs/scopepay-ai) | Experimental and development examples | [docs/proof/hosted-approve.mjs](https://github.com/yablokolabs/scopepay-ai/blob/2daf1d45791f9a11b3a80275bd8d6ff7689de475/docs/proof/hosted-approve.mjs) |
| [naibarn/SmartSpecPro](https://github.com/naibarn/SmartSpecPro) | Experimental and development examples | [apps/runner-app/src/moli_acceptance.rs](https://github.com/naibarn/SmartSpecPro/blob/ef8ddf3c2d3f05dfde5d38bb5bbb8a8571289e80/apps/runner-app/src/moli_acceptance.rs) |

The e2e maintainers merged the Moli adapter contributed by `ldm0` on 2026-11-17. The public npm registry returned 404 for `@e2e-dev/moli` on the review date. [Upstream PR](https://github.com/e2e-inc/e2e/pull/1843) · [Registry check](../data/review-2026-11-19-e2e.json)

## Held out of the README

| Repository | Review result |
| --- | --- |
| [Boom-Vitt/nose-erp](https://github.com/Boom-Vitt/nose-erp) | GitHub repository metadata returned 404; the public page also returned 404. Historical ERP integration could not be revalidated. |
| [EarlySalty/Deadlock-Twitch-Bot](https://github.com/EarlySalty/Deadlock-Twitch-Bot) | GitHub repository metadata returned 404. A cached public page was available, but current default-branch evidence could not be recovered. |
| [transparentCode/flipperAgent](https://github.com/transparentCode/flipperAgent) | GitHub repository metadata and the public page returned 404. The historical integration could not be revalidated. |
| [hamdansumedang/umroh-hpp-mvp](https://github.com/hamdansumedang/umroh-hpp-mvp) | Repository metadata and the full file tree were retrieved. Code search did not locate Moli, no Moli-named path was found, and .hermes.md did not mention it. The supplied integration claim remains unverified; this is not proof of absence. |
| [javedhamzabwn/muse-browser-automation](https://github.com/javedhamzabwn/muse-browser-automation) | GitHub repository metadata and the public page returned 404. No identity or deduplication with another Muse bridge is assumed. |
| [lyp88997/dsh-moli-browser](https://github.com/lyp88997/dsh-moli-browser) | GitHub repository metadata returned 404. A cached public page was available, but current default-branch evidence could not be recovered. |
| [ncdevshiv/NC-DSH](https://github.com/ncdevshiv/NC-DSH) | TOOLS-AUDIT.md mentions Moli providers, but the referenced packages/browser/browser-moli/src/index.ts and packages/web/web-fetch-moli/src/index.ts returned 404 and were absent from the captured default-branch tree. No current adapter was recovered; retained as a historical mention. [Audit document](https://github.com/ncdevshiv/NC-DSH/blob/3e779e64614e4f9f67b6727d2494e00d7fd93c25/TOOLS-AUDIT.md). |

## Changes from the historical classifications

- **Moli Web Research**, **chatctl in toolz**, and **A3S Search** have concrete Moli tooling or adapter evidence. Their earlier mention-only descriptions are not carried into the README.
- **Browser Bridge for Muse** is the canonical repository name returned for `rehantheorylab-pixel/muse-browser-automation`. The inaccessible `javedhamzabwn` repository is not assumed to be the same project.
- **Qianxun** is described narrowly as executable discovery and version checking, which is what the inspected module demonstrates.
- **SmartSpecPro** has a test-only Moli launcher excluded from default builds. It belongs with development examples.
- **laravel-domains** has a newer evaluation history covering subsequent versions and retests. The historical 1.1.23 report does not describe the current state of all Moli versions.
- **Aveli**, **govio-map**, **Hydra Downloader**, **llama.rs**, **Master Maps**, **Molifasi**, and **ScopePay AI** are listed as experimental or development examples, not evidence of production adoption.
- **Lumen** now has a dedicated browser integration document. Its inclusion describes the bundled tools, without inferring deployment scale or payment.

## Other unresolved names

**PapersFlow** and **ELITEA** were mentioned without concrete repository paths or original integration URLs. Public lookup did not recover an unambiguous Moli integration for this review. They remain leads for a future evidence-backed addition; failure to locate them is not evidence that no integration exists.

## Maintaining the list

Use the [contribution guidelines](../CONTRIBUTING.md). Keep future review snapshots as separate dated files. Updating a description or recovering a historical repository does not establish when adoption began.
