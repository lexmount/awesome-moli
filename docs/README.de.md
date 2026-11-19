# Awesome Moli [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
  <a href="../README.md">English</a> | <a href="README.zh-CN.md">简体中文</a> | <a href="README.ja.md">日本語</a> | <strong>Deutsch</strong> | <a href="README.fr.md">Français</a> | <a href="README.es.md">Español</a> | <a href="README.ko.md">한국어</a>
</p>

> Werkzeuge, Integrationen und Beispiele für [Moli](https://github.com/lexmount/moli), den quelloffenen Headless-Browser für KI-Agenten.

Entdecke Moli für Browserautomatisierung, Webextraktion, Agenten-Workflows und selbst gehostete Dienste. Einige Integrationen sind optional oder experimentell; beachte die Einrichtungshinweise des jeweiligen Projekts.

## Inhalt

- [Kernressourcen](#official-resources)
- [Integrationen](#integrations)
  - [Tests und QA](#testing-and-qa)
  - [Browserwerkzeuge und MCP](#browser-tools-and-mcp)
  - [Agenten und Arbeitsbereiche](#agents-and-workspaces)
  - [Webextraktion und Recherche](#web-extraction-and-research)
- [Community-Projekte](#community-projects)
  - [Forks und Weiterentwicklungen](#forks-and-derivatives)
  - [Deployment und Pakete](#deployment-and-packaging)
  - [Experimentelle Projekte und Entwicklungsbeispiele](#experimental-and-development-examples)

<a id="official-resources"></a>

## Kernressourcen

- [Moli](https://github.com/lexmount/moli) - Offizielles Repository mit Installationsanleitung, CLI-Nutzung und Dokumentation der Automatisierungsprotokolle.
- [Releases](https://github.com/lexmount/moli/releases) - Vorkompilierte Binärdateien und offizielle Versionshinweise.
- [Agent skills](https://github.com/lexmount/moli/tree/main/skills) - Offizielle Agenten-Skills für Seitenabrufe, Websuche und den Betrieb eines CDP-Servers.
- [WebMCP playground](https://github.com/lexmount/moli/tree/main/moli-playground/webmcp) - Skripte und Demos zum Finden und Aufrufen nativer WebMCP-Werkzeuge einer Website über Moli.
- [Webstone](https://github.com/lexmount/webstone) - Evaluierungsumgebung für Browser und Webwerkzeuge mit reproduzierbaren Aufgaben und aufgezeichneten Belegen.

<a id="integrations"></a>

## Integrationen

<a id="testing-and-qa"></a>

### Tests und QA

- [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - End-to-End-Testframework mit experimentellem Moli-Helper zur Verwaltung lokaler Prozesse und zur Verbindung mit bestehenden CDP-Endpunkten.
- [e2e](https://github.com/e2e-inc/e2e) - Startet mit `@e2e-dev/moli` für jeden parallelen Web-Test-Worker einen eigenen lokalen Moli-Browser und beendet ihn nach dem Einsatz automatisch.
- [KMJ CodeBridge](https://github.com/kmjtechno/kmj-codebridge) - MCP-Entwicklungswerkzeuge mit optionalen Moli-Extraktionsprüfungen für festgelegte öffentliche Seiten und Chrome als Rückfalloption für visuelle QA.

<a id="browser-tools-and-mcp"></a>

### Browserwerkzeuge und MCP

- [Browser Bridge for Muse](https://github.com/rehantheorylab-pixel/browser-bridge-for-muse) - Brücke für Browserautomatisierung mit optionalem Moli-Backend über Playwright und CDP.
- [chatctl](https://github.com/ironpark/toolz/tree/main/cli/chatctl) - Go-CLI zur Verwaltung von Chat-Websitzungen, mit Moli für den Headless-Zugriff und Chrome für die interaktive Anmeldung.
- [Delta Browser](https://github.com/DevAnimecx/deltabrowser) - MCP-Browserserver mit verwalteter Moli-Engine und isolierten Worker-Prozessen unter Linux x86_64.
- [dsh-moli](https://github.com/27painter/dsh-moli) - Community-Plugin für DeepSeek Harness zur Seitenextraktion, JavaScript-Auswertung, Erstellung von Screenshots und PDFs sowie Engine-Diagnose.
- [Moli Job Apply](https://github.com/mcaupybugs/claude-job-apply-skill-moli) - Experimenteller Skill zur Jobsuche, der Bewerbungsformulare mit Moli ausfüllt und vor dem Absenden eine Bestätigung verlangt.
- [Moli Web Research](https://github.com/assistifyai405/moli-webonderzoek) - Lokales MCP-Recherchewerkzeug in der Betaphase, das Quellenbelege zu ausgewählten Webseiten speichert und Seitenstände vergleicht.
- [Smart Tool](https://github.com/AllanSantos-DV/smart-tool-dist) - Windows-Distribution von Agentenwerkzeugen, die bei unzureichender HTTP-Extraktion JavaScript-Seiten mit Moli rendert und Chromium als Rückfalloption nutzt.

<a id="agents-and-workspaces"></a>

### Agenten und Arbeitsbereiche

- [A3S Code](https://github.com/A3S-Lab/Code) - Agentenframework, das eine überprüfte Moli-Laufzeit für sein Headless-Websuch-Backend bereitstellt.
- [agent-fabric](https://github.com/BlueTeam-OU/agent-fabric) - Verwaltungsplattform für Coding-Agenten, die Moli zum Lesen von Webseiten und Playwright MCP für skriptgesteuertes Browsen je Agent nutzt.
- [agnostic-router-kit](https://github.com/adelvillar1/agnostic-router-kit) - Workflow-Werkzeuge für Agenten, die Seiten zuerst mit Moli rendern und anschließend auf selbst gehostetes Firecrawl und HTTP zurückgreifen.
- [AION](https://github.com/JayCRL/AION) - Agenteninfrastruktur, deren web.read-Werkzeug mit Moli gerendertes Markdown oder strukturierte DOM-Daten liefert.
- [dsh-qq-bot](https://github.com/arrow1031-dev/dsh-qq-bot) - QQ-Bot-Integration mit optionalem lokalem Moli-Rendering für das Werkzeug qq_webfetch.
- [Internkim](https://github.com/yeomyeonggeori/internkim) - Agentenarbeitsbereich für Teams mit einer Moli-Browserlaufzeit zum Aufrufen öffentlicher Seiten.
- [Lumen](https://github.com/Andrea17982/Lumen) - Desktop-Arbeitsbereich für Agenten, der Moli bündelt und Browserwerkzeuge über mehrere Modell- und CLI-Adapter bereitstellt.
- [mem0-omp](https://github.com/millianlmx/mem0-omp) - Ausführungsumgebung für Coding-Agenten mit Moli-Browsern in Containern und einem authentifizierten HTTP/WebSocket-CDP-Gateway.
- [Qianxun](https://github.com/imxood/qianxun) - Tauri-Desktop-Arbeitsumgebung für DeepSeek Harness mit Erkennung lokaler Moli-Programme und Versionsprüfung.
- [Relay](https://github.com/arcwright42/Relay) - Agentenlaufzeit mit zeitlich und hinsichtlich der Ausgabe begrenzten Moli-Seitenabrufen sowie verwalteter Browserinstallation.
- [Wick](https://github.com/yogasw/wick) - Go-Agentenhost mit optionalem Moli-Browserkonnektor, CDP-Sitzungen und Markdown-Extraktion.

<a id="web-extraction-and-research"></a>

### Webextraktion und Recherche

- [888-url2md](https://github.com/tbdavid2019/888-url2md) - Dienst zur Umwandlung von Webseiten in Markdown mit lokalem Moli-CDP-Backend und separater Chrome-Rückfallstrategie.
- [A3S Search](https://github.com/A3S-Lab/Search) - Einbettbare Suchmaschine mit Moli-CLI-Renderer und begrenzter Anzahl gleichzeitiger Rendering-Prozesse.
- [Brains](https://github.com/YuniqueUnic/brains) - Versionierter Markdown-Wissensspeicher mit optionalem Moli-Rendering beim Import von URLs.
- [CTI Expert](https://github.com/7onez/cti-expert) - Werkzeugsammlung für Bedrohungsanalysen, die Moli zur DOM-Extraktion nach JavaScript-Ausführung nutzt und Chromium für visuelle Belege beibehält.
- [HEIS](https://github.com/u4399com-beep/heis) - System zum Sammeln von Romantexten mit einer Go-HTTP-Brücke für Moli-Abrufe und Skriptauswertung.
- [hermes-dev](https://github.com/Sucotasch/hermes-dev) - Hermes-Recherchetools, die Moli-Rendering als zusätzliche Stufe in der Rückfallkette zum Lesen von Seiten einsetzen.
- [Lens](https://github.com/bysages/lens) - TypeScript-Webwerkzeuge, die Moli über CDP für Screenshots und das Lesen von Seiten nutzen.
- [ModalPrism](https://github.com/MistLoom/ModalPrism) - Rust-Datenerfassungssystem, dessen Browseradapter dynamische Seiten über die Moli-CLI rendert.
- [molisnap](https://github.com/7a6163/molisnap) - SPA-Prerendering-Dienst für Suchcrawler und KI-Bots mit Caching und Vorwärmen über Sitemaps.
- [PageSift](https://github.com/YOLOW92/pagesift) - Rust-Dienst zur Web- und Dokumentextraktion mit Moli in einer Browserauswahlkette aus Lightpanda, Moli und Chrome.
- [stvdy](https://github.com/jettapindika/stvdy) - Lernarbeitsbereich, der Webquellen über eine Rückfallkette aus Exa, Moli und HTTP/readability importiert.
- [Vanilla](https://github.com/easylearnfromtw/vanilla) - KI-Arbeitsbereich für Familien mit ausdrücklich zu aktivierendem Moli-Extraktionsadapter, der eine separat konfigurierte Isolation ausgehender Netzwerkverbindungen voraussetzt.

<a id="community-projects"></a>

## Community-Projekte

<a id="forks-and-derivatives"></a>

### Forks und Weiterentwicklungen

- [Limo](https://github.com/Spxg/limo) - Führt JavaScript mit der vollständigen Web-API-Umgebung von Moli im Terminal aus, sodass Skripte DOM-Elemente erzeugen und auf Klicks reagieren können.
- [moli-stealth](https://github.com/Stravia-AI/moli-stealth) - Moli-Fork mit einem an Chrome angelehnten Netzwerkprofil und einer gemeinsamen Rust-Transportschicht für HTTP und WebSockets.
- [pilot](https://github.com/WSAdam/pilot) - Ein von Moli abgeleiteter Browser, den Playwright oder Playwright MCP direkt starten können und der auf Wunsch die Aktionen des Agenten in einem Fenster zeigt.

<a id="deployment-and-packaging"></a>

### Deployment und Pakete

Installationsrezepte und Deployment-Vorlagen aus der Community.

- [1Panel App](https://github.com/skingko/1panel_app/tree/localApps/apps/x-moli) - Von der Community gepflegte 1Panel-Anwendungsdefinition und Docker-Image-Erstellung für Moli.
- [A3S CLI](https://github.com/A3S-Lab/CLI) - A3S-Kommandozeilendistribution mit gebündelter, zielplattformspezifischer Moli-Laufzeit.
- [Homebrew Moli](https://github.com/hoishing/homebrew-moli) - Community-Homebrew-Tap zur Installation von Moli-Binärdateien und den zugehörigen offiziellen Agenten-Skills.
- [Lattice](https://github.com/mytecor/lattice/tree/main/profiles/moli) - NixOS-Moli-Dienst mit entferntem CDP-Zugriff, gehosteten DevTools und Caddy/Authentik-Zugang.
- [moli-snap](https://github.com/sidalit/moli-snap) - Inoffizielles Snap-Paket zum Ausführen der Moli-CLI und des Automatisierungsservers unter Linux.
- [orbsh/nixos](https://github.com/orbsh/nixos/blob/main/modules/system/units/moli.nix) - NixOS-Paketdefinition für fest versionierte Moli-Release-Binärdateien und deren Laufzeitabhängigkeiten.
- [Railway Moli](https://github.com/two-workspaces/moli) - Railway-Deployment-Vorlage mit tokenbasiert geschütztem Caddy-Gateway und Umschreibung öffentlicher WebSocket-Endpunkte.

<a id="experimental-and-development-examples"></a>

### Experimentelle Projekte und Entwicklungsbeispiele

Prototypen, Entwicklungsskripte und Evaluierungsberichte. Die genannten Testergebnisse stammen von den jeweiligen Autoren.

- [Aveli](https://github.com/pkmdev-sec/aveli) - Experimentelle Moli-Laufzeit und Kompatibilitätsprüfungen für einen Browseragenten.
- [govio-map](https://github.com/chenxinma/govio-map) - CDP-Smoke-Testskript zur Prüfung von Eingabefokus und Validierung im Einstellungsdialog einer Anwendung.
- [Hydra Downloader](https://github.com/juanpimg/hydradownloader) - Entwicklungsskripte, die mit Moli-CDP responsive Layouts und Download-Abläufe prüfen.
- [laravel-domains](https://github.com/yepbro/laravel-domains) - Crawler-Projekt mit versionsbezogenen Moli-Bewertungen, Regressionen, erneuten Tests und Chromium-Vergleichen.
- [llama.rs](https://github.com/yablokolabs/llama.rs) - Browsertestskript, das mit Moli die JavaScript-Oberfläche einer Rust/WASM-Chat-Anwendung prüft.
- [Master Maps](https://github.com/0bifthenelse/master-maps) - Kartenanwendung mit Moli-basierten End-to-End-Skripten und ausdrücklicher Rückfalloption auf lokales Chromium.
- [Molifasi](https://github.com/A3S-Lab/Molifasi) - Rust-Prototyp eines Browseragenten, der Moli-CDP-Beobachtungen und -Aktionen mit Apofasi-Entscheidungen verbindet.
- [ScopePay AI](https://github.com/yablokolabs/scopepay-ai) - PayPal-Sandbox-Beispiel, das Moli-CDP für die Freigabe des Bezahlvorgangs durch den Käufer nutzt.
- [SmartSpecPro](https://github.com/naibarn/SmartSpecPro) - Separat vom Standard-Build verfügbarer Starter für Moli-Akzeptanztests unter Linux ohne Root-Rechte.

## Mitwirken

Moli-Forks, Weiterentwicklungen und neue Einsatzmöglichkeiten sind willkommen. Wie du ein Projekt vorschlägst oder einen Eintrag verbesserst, steht in den [Beitragsrichtlinien](../CONTRIBUTING.md).

## Anmerkungen

Am **2026-11-19** wurden öffentlicher Quellcode und Projektdokumentation geprüft. Produktiveinsatz, Kundenbeziehungen und die unabhängige Bestätigung von Testergebnissen lagen außerhalb dieser Prüfung. Das [Prüfprotokoll](REVIEW.md) enthält Links zu den geprüften Versionen und den erfassten Belegen sowie Hinweise zu früheren Erwähnungen und nicht erreichbaren Repositories.
