<h1 align="center">Awesome Moli</h1>

<p align="center">
  <a href="../README.md">English</a> | <a href="README.zh-CN.md">简体中文</a> | <a href="README.ja.md">日本語</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.es.md">Español</a> | <strong>한국어</strong>
</p>

> [Moli](https://github.com/lexmount/moli)는 AI 에이전트를 위한 오픈 소스 헤드리스 브라우저입니다. 이 목록은 Moli를 활용하거나 확장하거나 배포하는 프로젝트를 모아 브라우저 자동화 도구, 프레임워크 연동, 파생 프로젝트, 배포 방법과 개발 사례를 소개합니다.

## 목차

- [포크와 파생 프로젝트](#forks-and-derivatives)
- [테스트 및 QA 도구](#testing-and-qa-tools)
- [브라우저 자동화와 워크플로](#browser-automation-and-workflows)
- [웹 렌더링과 데이터 추출](#web-rendering-and-extraction)
- [에이전트 프레임워크와 작업 공간](#agent-frameworks-and-workspaces)
- [패키징과 배포](#packaging-and-deployment)
- [개발 사례와 평가](#development-examples-and-evaluations)

<a id="forks-and-derivatives"></a>

## 포크와 파생 프로젝트

- **[Limo](https://github.com/Spxg/limo) - 터미널에서 Moli의 브라우저 Web API 전체를 사용해 JavaScript를 실행합니다.**
- [moli-stealth](https://github.com/Stravia-AI/moli-stealth) - Moli의 HTTP 및 WebSocket 연결에 Chrome과 유사한 네트워크 설정을 적용합니다.
- [pilot](https://github.com/WSAdam/pilot) - Playwright MCP로 에이전트가 웹을 탐색하는 모습을 창에서 실시간으로 보여 줍니다.

<a id="testing-and-qa"></a>
<a id="testing-and-qa-tools"></a>

## 테스트 및 QA 도구

- [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - 실험적인 Moli 백엔드로 엔드 투 엔드 테스트를 실행합니다.
- **[e2e](https://github.com/e2e-inc/e2e) - 상위 프로젝트에 병합된 Moli 어댑터가 병렬 테스트 프로세스마다 로컬 브라우저를 하나씩 실행합니다.**
- [KMJ CodeBridge](https://github.com/kmjtechno/kmj-codebridge) - 필요하면 Moli로 지정된 공개 테스트 페이지에서 본문을 추출할 수 있는지 확인합니다.

<a id="browser-tools-and-mcp"></a>
<a id="browser-automation-and-workflows"></a>

## 브라우저 자동화와 워크플로

- [Browser Bridge for Muse](https://github.com/rehantheorylab-pixel/browser-bridge-for-muse) - Muse에서 Playwright 자동화용 로컬 브라우저로 Moli를 선택할 수 있습니다.
- [chatctl](https://github.com/ironpark/toolz/tree/main/cli/chatctl) - Chrome에서 한 번 로그인하면 Moli로 터미널에서 대화 기록을 읽을 수 있습니다.
- [Delta Browser](https://github.com/DevAnimecx/deltabrowser) - x86_64 Linux에서 샌드박스로 격리된 Moli 프로세스로 MCP 브라우저 세션을 실행합니다.
- **[dsh-moli](https://github.com/27painter/dsh-moli) - 동적 웹페이지를 Markdown으로 변환하는 DeepSeek Harness 커뮤니티 플러그인입니다.**
- [Moli Job Apply](https://github.com/mcaupybugs/claude-job-apply-skill-moli) - 지원서를 작성하고 제출 전에 사용자 확인을 받는 실험적인 구직 도우미입니다.

<a id="web-extraction-and-research"></a>
<a id="web-rendering-and-extraction"></a>

## 웹 렌더링과 데이터 추출

- [888-url2md](https://github.com/tbdavid2019/888-url2md) - 여러 웹페이지를 한꺼번에 Markdown으로 변환하고 JavaScript가 필요한 페이지는 Moli로 렌더링합니다.
- [A3S Search](https://github.com/A3S-Lab/Search) - 검색 결과에서 JavaScript가 필요한 페이지를 Moli로 읽습니다.
- [Brains](https://github.com/YuniqueUnic/brains) - Moli로 동적 웹페이지를 가져와 버전 기록이 있는 Markdown 노트로 저장할 수 있습니다.
- [CTI Expert](https://github.com/7onez/cti-expert) - 위협 인텔리전스 조사에 필요한 웹 콘텐츠를 JavaScript 실행 후 Moli로 수집합니다.
- [HEIS](https://github.com/u4399com-beep/heis) - Moli로 동적으로 불러오는 웹소설의 각 회차를 수집할 수 있습니다.
- [hermes-dev](https://github.com/Sucotasch/hermes-dev) - Hermes Deep Research가 일반 방식으로 본문을 읽지 못하면 Moli로 페이지를 렌더링합니다.
- [Lens](https://github.com/bysages/lens) - HTTP API로 Moli를 호출해 웹페이지의 스크린샷을 찍을 수 있습니다.
- [ModalPrism](https://github.com/MistLoom/ModalPrism) - Moli로 렌더링한 동적 웹페이지를 보관해 수집 당시의 내용을 다시 볼 수 있습니다.
- [Moli Web Research](https://github.com/assistifyai405/moli-webonderzoek) - 저장된 웹페이지 스냅샷 두 개를 비교하는 베타 버전의 로컬 MCP 도구입니다.
- [molisnap](https://github.com/7a6163/molisnap) - 싱글 페이지 앱을 검색 크롤러와 AI 봇이 읽을 수 있는 HTML로 미리 렌더링합니다.
- [PageSift](https://github.com/YOLOW92/pagesift) - Lightpanda가 읽지 못하는 iframe 콘텐츠를 Moli로 가져옵니다.
- [Smart Tool](https://github.com/AllanSantos-DV/smart-tool-dist) - Windows 코딩 에이전트가 HTTP 요청만으로 본문을 얻지 못하면 Moli를 사용할 수 있습니다.
- [stvdy](https://github.com/jettapindika/stvdy) - Exa에서 본문을 가져오지 못하면 Moli로 웹페이지를 학습 자료로 가져옵니다.
- [Vanilla](https://github.com/easylearnfromtw/vanilla) - 외부로 나가는 네트워크 트래픽을 격리한 뒤 Moli를 켜서 공개 웹페이지 본문을 가져올 수 있습니다.

<a id="agents-and-workspaces"></a>
<a id="agent-frameworks-and-workspaces"></a>

## 에이전트 프레임워크와 작업 공간

- [A3S Code](https://github.com/A3S-Lab/Code) - 코딩 에이전트가 웹을 검색할 수 있도록 검증된 Moli 브라우저를 자동으로 준비합니다.
- [agent-fabric](https://github.com/BlueTeam-OU/agent-fabric) - 코딩 에이전트마다 별도의 임시 Moli 브라우저 세션을 제공합니다.
- [agnostic-router-kit](https://github.com/adelvillar1/agnostic-router-kit) - 워크플로에서 JavaScript 페이지를 읽을 때 로컬 Moli를 먼저 사용합니다.
- [AION](https://github.com/JayCRL/AION) - Moli로 읽은 동적 웹페이지를 에이전트 작업 공간에 카드 형태로 표시합니다.
- [dsh-qq-bot](https://github.com/arrow1031-dev/dsh-qq-bot) - QQ 봇이 필요에 따라 로컬 Moli로 공유된 링크를 Markdown으로 읽을 수 있습니다.
- [Internkim](https://github.com/yeomyeonggeori/internkim) - 팀의 AI 어시스턴트가 로컬 Moli로 공개 웹페이지를 탐색할 수 있습니다.
- [Lumen](https://github.com/Andrea17982/Lumen) - Claude Code와 Codex 같은 코딩 에이전트가 데스크톱에서 함께 쓰는 Moli 브라우저 도구를 내장합니다.
- [mem0-omp](https://github.com/millianlmx/mem0-omp) - 코딩 에이전트가 토큰 인증을 거쳐 컨테이너 안의 Moli 브라우저에 접속할 수 있습니다.
- [Qianxun](https://github.com/imxood/qianxun) - DeepSeek Harness 데스크톱 앱에서 로컬 Moli 설치 여부와 버전을 확인합니다.
- [Relay](https://github.com/arcwright42/Relay) - Moli로 링크를 읽다가 페이지 응답 시간이 초과돼도 프롬프트를 제출할 수 있습니다.
- [Wick](https://github.com/yogasw/wick) - Go 에이전트가 필요에 따라 로컬 Moli로 웹페이지를 Markdown으로 읽을 수 있습니다.

<a id="deployment-and-packaging"></a>
<a id="packaging-and-deployment"></a>

## 패키징과 배포

커뮤니티에서 제공하는 설치 구성과 배포 템플릿.

- [1Panel App](https://github.com/skingko/1panel_app/tree/localApps/apps/x-moli) - 커뮤니티 패키지를 통해 1Panel에서 Moli를 배포할 수 있습니다.
- [A3S CLI](https://github.com/A3S-Lab/CLI) - A3S 명령줄 도구에 대상 플랫폼용 Moli 런타임을 함께 제공합니다.
- [Homebrew Moli](https://github.com/hoishing/homebrew-moli) - Moli와 해당 버전의 공식 에이전트 스킬을 함께 설치하는 커뮤니티 Homebrew 저장소입니다.
- [Lattice](https://github.com/mytecor/lattice/tree/main/profiles/moli) - NixOS에서 Moli를 호스팅해 원격에서 DevTools로 웹페이지를 디버깅할 수 있습니다.
- [moli-snap](https://github.com/sidalit/moli-snap) - 스크린샷과 PDF에 쓸 글꼴을 Moli와 함께 제공하는 비공식 Linux Snap 패키지입니다.
- [orbsh/nixos](https://github.com/orbsh/nixos/blob/main/modules/system/units/moli.nix) - Moli 버전과 체크섬을 고정해 NixOS에서 같은 바이너리를 설치할 수 있습니다.
- [Railway Moli](https://github.com/two-workspaces/moli) - Railway에 Moli를 배포하고 토큰 인증으로 브라우저에 원격 접속할 수 있습니다.

<a id="experimental-and-development-examples"></a>
<a id="development-examples-and-evaluations"></a>

## 개발 사례와 평가

프로토타입, 개발 스크립트 및 평가 보고서입니다. 테스트 결과는 각 작성자의 보고에 따른 것입니다.

- [Aveli](https://github.com/pkmdev-sec/aveli) - 브라우저 에이전트가 로컬 Moli에 연결할 수 있는지 확인하는 실험적 테스트입니다.
- [govio-map](https://github.com/chenxinma/govio-map) - Moli로 설정 입력란에 한 글자씩 쓰면서 키보드 포커스가 유지되는지 확인합니다.
- [Hydra Downloader](https://github.com/juanpimg/hydradownloader) - Moli로 여러 휴대폰 화면 너비에서 다운로드 페이지가 화면 밖으로 넘치는지 확인합니다.
- [laravel-domains](https://github.com/yepbro/laravel-domains) - 여러 Moli 버전과 Chromium에서 웹 크롤러의 동작을 비교합니다.
- [llama.rs](https://github.com/yablokolabs/llama.rs) - 로컬 WebAssembly 채팅 데모가 질문에 답하는지 Moli로 확인합니다.
- [Master Maps](https://github.com/0bifthenelse/master-maps) - Moli로 3D 지도를 엔드 투 엔드 테스트하고 필요하면 로컬 Chromium을 사용합니다.
- [Molifasi](https://github.com/A3S-Lab/Molifasi) - Apofasi가 다음 동작을 고르면 Moli가 웹페이지에서 실행하는 프로토타입 에이전트입니다.
- [ScopePay AI](https://github.com/yablokolabs/scopepay-ai) - PayPal 샌드박스에서 구매자가 결제 시 승인을 완료하는 흐름을 Moli로 테스트합니다.
- [SmartSpecPro](https://github.com/naibarn/SmartSpecPro) - Linux에서 루트 권한 없이 실행하는 인수 테스트에만 Moli를 사용합니다.

## 기여하기

Moli 포크와 파생 프로젝트, 새로운 활용 사례를 환영합니다. 프로젝트를 소개하거나 기존 항목을 개선하려면 [기여 가이드](../CONTRIBUTING.md)를 참고하세요.

## 참고

**2026-11-19**에 공개 소스 코드와 프로젝트 문서를 검토했습니다. 운영 환경에서의 사용, 고객 관계, 테스트 결과의 독립적 재현은 검토 범위에서 제외했습니다. 확인한 커밋과 근거 자료, 과거 언급과 접근할 수 없었던 저장소는 [검토 기록](REVIEW.md)에 정리했습니다.
