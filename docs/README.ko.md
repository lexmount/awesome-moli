# Awesome Moli [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
  <a href="../README.md">English</a> | <a href="README.zh-CN.md">简体中文</a> | <a href="README.ja.md">日本語</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.es.md">Español</a> | <strong>한국어</strong>
</p>

> AI 에이전트용 오픈 소스 헤드리스 브라우저 [Moli](https://github.com/lexmount/moli)의 도구, 통합 및 활용 예제.

브라우저 자동화, 웹 추출, 에이전트 워크플로 및 자체 호스팅 서비스에서 Moli를 활용하는 방법을 소개합니다. 일부 통합은 선택 기능이거나 실험 단계이므로 각 프로젝트의 설정 가이드를 확인하세요.

## 목차

- [공식 자료](#official-resources)
- [포크와 파생 프로젝트](#forks-and-derivatives)
- [브라우저 도구와 MCP](#browser-tools-and-mcp)
- [에이전트와 작업 공간](#agents-and-workspaces)
- [웹 추출과 조사](#web-extraction-and-research)
- [테스트와 QA](#testing-and-qa)
- [배포와 패키징](#deployment-and-packaging)
- [실험 및 개발 사례](#experimental-and-development-examples)

<a id="official-resources"></a>

## 공식 자료

- [Moli](https://github.com/lexmount/moli) - 공식 저장소, 설치 안내, CLI 사용법 및 자동화 프로토콜 문서.
- [Releases](https://github.com/lexmount/moli/releases) - 미리 빌드된 바이너리와 공식 릴리스 노트.
- [Agent skills](https://github.com/lexmount/moli/tree/main/skills) - 페이지 가져오기, 웹 검색 및 CDP 서버 실행을 위한 공식 에이전트 스킬.
- [WebMCP playground](https://github.com/lexmount/moli/tree/main/moli-playground/webmcp) - Moli로 사이트의 네이티브 WebMCP 도구를 찾고 호출하는 스크립트와 데모.
- [Webstone](https://github.com/lexmount/webstone) - 재현 가능한 작업과 실행 증거를 제공하는 브라우저 및 웹 도구 평가 프레임워크.

<a id="forks-and-derivatives"></a>

## 포크와 파생 프로젝트

- [moli-stealth](https://github.com/Stravia-AI/moli-stealth) - Chrome을 모델로 한 네트워크 프로필을 제공하고 HTTP와 WebSocket에 공통 Rust 전송 계층을 사용하는 Moli 포크.
- [pilot](https://github.com/WSAdam/pilot) - Playwright와 Playwright MCP에서 직접 실행할 수 있는 Moli 기반 브라우저. 별도 창을 열어 에이전트가 웹페이지를 조작하는 모습을 볼 수 있습니다. [Playwright 설정 안내](https://github.com/WSAdam/pilot/blob/main/pilot/README.md)

<a id="browser-tools-and-mcp"></a>

## 브라우저 도구와 MCP

- [Browser Bridge for Muse](https://github.com/rehantheorylab-pixel/browser-bridge-for-muse) - Playwright와 CDP를 통해 선택적 Moli 백엔드를 제공하는 브라우저 자동화 브리지.
- [chatctl](https://github.com/ironpark/toolz/tree/main/cli/chatctl) - 채팅 웹 세션을 관리하는 Go CLI로, 헤드리스 접근에는 Moli를, 대화형 로그인에는 Chrome을 사용.
- [Delta Browser](https://github.com/DevAnimecx/deltabrowser) - Linux x86_64에서 관리형 Moli 엔진과 샌드박스 작업 프로세스를 제공하는 MCP 브라우저 서버.
- [dsh-moli](https://github.com/27painter/dsh-moli) - 페이지 추출, JavaScript 실행, 스크린샷, PDF 및 엔진 진단을 지원하는 DeepSeek Harness 커뮤니티 플러그인.
- [Limo](https://github.com/Spxg/limo) - Spxg의 Moli 포크에서 `moli-core`를 가져와 내장한 명령줄 JavaScript 실행기. 스크립트에서 DOM을 조작하고 브라우저 이벤트를 처리할 수 있습니다.
- [Moli Job Apply](https://github.com/mcaupybugs/claude-job-apply-skill-moli) - Moli로 지원서를 작성하고 제출 전에 사용자 확인을 요구하는 실험적 구직 스킬.
- [Moli Web Research](https://github.com/assistifyai405/moli-webonderzoek) - 지정한 URL 읽기, 출처 증거 보관, 페이지 스냅샷 비교를 지원하는 로컬 MCP 조사 도구로, 현재 베타 버전.
- [Smart Tool](https://github.com/AllanSantos-DV/smart-tool-dist) - HTTP 추출만으로 부족한 JavaScript 페이지에 Moli를 사용하고 Chromium으로 대체할 수 있는 Windows 에이전트 도구 배포판.

<a id="agents-and-workspaces"></a>

## 에이전트와 작업 공간

- [A3S Code](https://github.com/A3S-Lab/Code) - 헤드리스 웹 검색 백엔드를 위해 검증된 Moli 런타임을 준비하는 에이전트 프레임워크.
- [agent-fabric](https://github.com/BlueTeam-OU/agent-fabric) - Moli로 웹을 읽고 Playwright MCP를 통해 에이전트별 스크립트 탐색을 수행하는 코딩 에이전트 관리 플랫폼.
- [agnostic-router-kit](https://github.com/adelvillar1/agnostic-router-kit) - Moli로 페이지를 먼저 렌더링한 뒤 자체 호스팅 Firecrawl과 일반 HTTP를 대체 경로로 사용하는 에이전트 워크플로 도구.
- [AION](https://github.com/JayCRL/AION) - web.read 도구에서 Moli를 사용해 렌더링된 Markdown 또는 구조화된 DOM 데이터를 반환하는 에이전트 기반 시스템.
- [dsh-qq-bot](https://github.com/arrow1031-dev/dsh-qq-bot) - qq_webfetch 도구에 선택적 로컬 Moli 렌더링 경로를 제공하는 QQ 봇 연동.
- [Internkim](https://github.com/yeomyeonggeori/internkim) - 공개 페이지 탐색을 위한 Moli 브라우저 런타임을 갖춘 팀 에이전트 작업 공간.
- [Lumen](https://github.com/Andrea17982/Lumen) - Moli를 포함하고 여러 모델 및 CLI 어댑터에서 브라우저 도구를 공유하는 데스크톱 에이전트 작업 공간.
- [mem0-omp](https://github.com/millianlmx/mem0-omp) - 컨테이너형 Moli 브라우저와 인증된 HTTP/WebSocket CDP 게이트웨이를 갖춘 코딩 에이전트 실행 환경.
- [Qianxun](https://github.com/imxood/qianxun) - 로컬 Moli 실행 파일 탐색과 버전 확인을 지원하는 DeepSeek Harness용 Tauri 데스크톱 작업 환경.
- [Relay](https://github.com/arcwright42/Relay) - 시간과 출력 크기를 제한한 Moli 페이지 가져오기 및 브라우저 설치 관리를 제공하는 에이전트 런타임.
- [Wick](https://github.com/yogasw/wick) - 선택적 Moli 브라우저 커넥터, CDP 세션 및 Markdown 추출 기능을 갖춘 Go 에이전트 호스트.

<a id="web-extraction-and-research"></a>

## 웹 추출과 조사

- [888-url2md](https://github.com/tbdavid2019/888-url2md) - 로컬 Moli CDP 백엔드와 별도의 Chrome 대체 정책을 갖춘 페이지의 Markdown 변환 서비스.
- [A3S Search](https://github.com/A3S-Lab/Search) - Moli CLI 렌더러와 동시 렌더링 수 제한을 제공하는 내장형 검색 엔진.
- [Brains](https://github.com/YuniqueUnic/brains) - URL을 가져올 때 Moli 렌더링을 선택할 수 있는 버전 관리형 Markdown 지식 저장소.
- [CTI Expert](https://github.com/7onez/cti-expert) - JavaScript 실행 후 DOM 추출에는 Moli를 사용하고 시각적 증거에는 Chromium을 유지하는 위협 인텔리전스 도구.
- [HEIS](https://github.com/u4399com-beep/heis) - Moli의 페이지 가져오기와 스크립트 실행을 Go HTTP 브리지로 제공하는 소설 수집 시스템.
- [hermes-dev](https://github.com/Sucotasch/hermes-dev) - 페이지 읽기의 대체 경로에 Moli 렌더링을 추가한 Hermes 조사 도구.
- [Lens](https://github.com/bysages/lens) - CDP를 통해 Moli로 스크린샷을 만들고 페이지를 읽는 TypeScript 웹 도구 모음.
- [ModalPrism](https://github.com/MistLoom/ModalPrism) - 브라우저 접근 모듈에서 Moli CLI로 동적 페이지를 렌더링하는 Rust 데이터 수집 시스템.
- [molisnap](https://github.com/7a6163/molisnap) - 캐싱과 사이트맵 사전 로딩을 지원하는 검색 크롤러 및 AI 봇용 SPA 사전 렌더링 서비스.
- [PageSift](https://github.com/YOLOW92/pagesift) - Lightpanda → Moli → Chrome 브라우저 선택 경로에 Moli를 포함하는 Rust 웹·문서 추출 서비스.
- [stvdy](https://github.com/jettapindika/stvdy) - Exa, Moli, HTTP/readability 대체 경로를 통해 웹 자료를 가져오는 학습 작업 공간.
- [Vanilla](https://github.com/easylearnfromtw/vanilla) - 명시적으로 활성화하는 Moli 페이지 추출 어댑터를 갖춘 가족용 AI 작업 공간으로, 별도의 아웃바운드 네트워크 격리가 필요.

<a id="testing-and-qa"></a>

## 테스트와 QA

- [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - 로컬 프로세스 관리와 기존 CDP 엔드포인트 연결을 지원하는 실험적 Moli 헬퍼를 갖춘 종단 간 테스트 프레임워크.
- [KMJ CodeBridge](https://github.com/kmjtechno/kmj-codebridge) - 고정된 공개 페이지에 선택적 Moli 추출 검사를 수행하고 Chrome 시각 QA로 대체할 수 있는 MCP 개발 도구.

<a id="deployment-and-packaging"></a>

## 배포와 패키징

커뮤니티에서 제공하는 설치 구성과 배포 템플릿.

- [1Panel App](https://github.com/skingko/1panel_app/tree/localApps/apps/x-moli) - 커뮤니티에서 관리하는 Moli용 1Panel 애플리케이션 구성과 Docker 이미지 빌드.
- [A3S CLI](https://github.com/A3S-Lab/CLI) - 대상 플랫폼별 Moli 런타임을 포함하는 A3S 명령줄 배포판.
- [Homebrew Moli](https://github.com/hoishing/homebrew-moli) - Moli 바이너리와 해당 버전의 공식 에이전트 스킬을 설치하는 커뮤니티 Homebrew tap.
- [Lattice](https://github.com/mytecor/lattice/tree/main/profiles/moli) - 원격 CDP 접근, 호스팅된 DevTools 및 Caddy/Authentik 진입점을 제공하는 NixOS Moli 서비스.
- [moli-snap](https://github.com/sidalit/moli-snap) - Linux에서 Moli CLI와 자동화 서버를 실행하기 위한 비공식 Snap 패키지.
- [orbsh/nixos](https://github.com/orbsh/nixos/blob/main/modules/system/units/moli.nix) - 버전을 고정한 Moli 릴리스 바이너리와 런타임 의존성을 위한 NixOS 패키지 정의.
- [Railway Moli](https://github.com/two-workspaces/moli) - 토큰으로 보호되는 Caddy 게이트웨이와 공개 WebSocket 주소 재작성을 제공하는 Railway 배포 템플릿.

<a id="experimental-and-development-examples"></a>

## 실험 및 개발 사례

프로토타입, 개발 스크립트 및 평가 보고서입니다. 테스트 결과는 각 작성자의 보고에 따른 것입니다.

- [Aveli](https://github.com/pkmdev-sec/aveli) - 브라우저 에이전트용 실험적 Moli 런타임과 호환성 검사 도구.
- [govio-map](https://github.com/chenxinma/govio-map) - 애플리케이션 설정 대화상자의 입력 포커스와 유효성 검사를 확인하는 CDP 스모크 테스트 스크립트.
- [Hydra Downloader](https://github.com/juanpimg/hydradownloader) - Moli CDP로 반응형 레이아웃과 다운로드 흐름을 확인하는 개발 스크립트.
- [laravel-domains](https://github.com/yepbro/laravel-domains) - 버전별 Moli 평가, 회귀 문제, 재시험 및 Chromium 비교를 기록하는 크롤러 프로젝트.
- [llama.rs](https://github.com/yablokolabs/llama.rs) - Moli로 Rust/WASM 채팅 애플리케이션의 JavaScript 인터페이스를 시험하는 브라우저 테스트 스크립트.
- [Master Maps](https://github.com/0bifthenelse/master-maps) - Moli 기반 종단 간 테스트 스크립트와 명시적인 로컬 Chromium 대체 경로를 갖춘 지도 애플리케이션.
- [Molifasi](https://github.com/A3S-Lab/Molifasi) - Moli CDP의 관찰·동작을 Apofasi의 의사결정과 결합한 Rust 브라우저 에이전트 프로토타입.
- [ScopePay AI](https://github.com/yablokolabs/scopepay-ai) - 구매자 승인 흐름에 Moli CDP를 사용하는 PayPal 샌드박스 결제 예제.
- [SmartSpecPro](https://github.com/naibarn/SmartSpecPro) - 루트 권한 없는 Linux 환경용 Moli 인수 테스트 실행기로, 기본 빌드에서는 제외.

## 기여하기

Moli 포크와 파생 프로젝트, 새로운 활용 사례를 환영합니다. 프로젝트를 소개하거나 기존 항목을 개선하려면 [기여 가이드](../CONTRIBUTING.md)를 참고하세요.

## 참고

**2026-11-19**에 공개 소스 코드와 프로젝트 문서를 검토했습니다. 운영 환경에서의 사용, 고객 관계, 테스트 결과의 독립적 재현은 검토 범위에서 제외했습니다. 확인한 커밋과 근거 자료, 과거 언급과 접근할 수 없었던 저장소는 [검토 기록](REVIEW.md)에 정리했습니다.
