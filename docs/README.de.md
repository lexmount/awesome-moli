<h1 align="center">Awesome Moli</h1>

<p align="center">
  <a href="../README.md">English</a> | <a href="README.zh-CN.md">简体中文</a> | <a href="README.ja.md">日本語</a> | <strong>Deutsch</strong> | <a href="README.fr.md">Français</a> | <a href="README.es.md">Español</a> | <a href="README.ko.md">한국어</a>
</p>

> [Moli](https://github.com/lexmount/moli) ist ein quelloffener Headless-Browser für KI-Agenten. Diese Liste stellt Projekte vor, die Moli nutzen, erweitern oder verteilen, darunter Werkzeuge zur Browserautomatisierung, Framework-Integrationen, Forks, Deployment-Lösungen und Entwicklungsbeispiele.

## Inhalt

- [Forks und Weiterentwicklungen](#forks-and-derivatives)
- [Test- und QA-Werkzeuge](#testing-and-qa-tools)
- [Browserautomatisierung und Workflows](#browser-automation-and-workflows)
- [Web-Rendering und Datenextraktion](#web-rendering-and-extraction)
- [Agenten-Frameworks und Arbeitsbereiche](#agent-frameworks-and-workspaces)
- [Paketierung und Deployment](#packaging-and-deployment)
- [Entwicklungsbeispiele und Evaluierungen](#development-examples-and-evaluations)

<a id="forks-and-derivatives"></a>

## Forks und Weiterentwicklungen

- **[Limo](https://github.com/Spxg/limo) - Führt JavaScript im Terminal mit allen Browser-Web-APIs von Moli aus.**
- [moli-stealth](https://github.com/Stravia-AI/moli-stealth) - Gibt Moli für HTTP- und WebSocket-Verbindungen ein Netzwerkprofil nach dem Vorbild von Chrome.
- [pilot](https://github.com/WSAdam/pilot) - Zeigt in einem Fenster live, wie ein Agent mit Playwright MCP im Web navigiert.

<a id="testing-and-qa"></a>
<a id="testing-and-qa-tools"></a>

## Test- und QA-Werkzeuge

- [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - Führt End-to-End-Tests mit einem experimentellen Moli-Backend aus.
- **[e2e](https://github.com/e2e-inc/e2e) - Testet Abläufe wie den Checkout in Moli mit Anweisungen in natürlicher Sprache und wiederholt geprüfte Aktionen ohne erneuten Modellaufruf.**
- [KMJ CodeBridge](https://github.com/kmjtechno/kmj-codebridge) - Kann mit Moli prüfen, ob sich Text aus vorgegebenen öffentlichen Testseiten extrahieren lässt.

<a id="browser-tools-and-mcp"></a>
<a id="browser-automation-and-workflows"></a>

## Browserautomatisierung und Workflows

- [Browser Bridge for Muse](https://github.com/rehantheorylab-pixel/browser-bridge-for-muse) - Bietet Muse den lokalen Moli-Browser als Option für die Playwright-Automatisierung.
- [chatctl](https://github.com/ironpark/toolz/tree/main/cli/chatctl) - Nutzt deine Chrome-Anmeldung, um mit Moli Chatverläufe im Terminal zu lesen.
- [Delta Browser](https://github.com/DevAnimecx/deltabrowser) - Führt MCP-Browsersitzungen unter x86_64-Linux in isolierten Moli-Prozessen aus.
- **[dsh-moli](https://github.com/27painter/dsh-moli) - Ein Community-Plugin, das dynamische Webseiten für DeepSeek Harness in Markdown umwandelt.**
- [Moli Job Apply](https://github.com/mcaupybugs/claude-job-apply-skill-moli) - Dieser experimentelle Assistent füllt Bewerbungsformulare aus und fragt vor dem Absenden nach.

<a id="web-extraction-and-research"></a>
<a id="web-rendering-and-extraction"></a>

## Web-Rendering und Datenextraktion

- [888-url2md](https://github.com/tbdavid2019/888-url2md) - Wandelt Webseiten stapelweise in Markdown um und rendert JavaScript-Seiten mit Moli.
- [A3S Search](https://github.com/A3S-Lab/Search) - Liest mit Moli Suchtreffer, deren Inhalte erst durch JavaScript sichtbar werden.
- [Brains](https://github.com/YuniqueUnic/brains) - Kann dynamische Webseiten mit Moli als Markdown-Notizen mit Versionsverlauf speichern.
- [CTI Expert](https://github.com/7onez/cti-expert) - Erfasst für die Bedrohungsanalyse mit Moli Webseiteninhalte, die JavaScript nachlädt.
- [HEIS](https://github.com/u4399com-beep/heis) - Kann mit Moli dynamisch geladene Kapitel von Online-Romanen erfassen.
- [hermes-dev](https://github.com/Sucotasch/hermes-dev) - Rendert Seiten für Hermes Deep Research mit Moli, wenn die normale Textextraktion scheitert.
- [Lens](https://github.com/bysages/lens) - Bietet eine HTTP-API für Webseiten-Screenshots mit Moli.
- [ModalPrism](https://github.com/MistLoom/ModalPrism) - Archiviert mit Moli gerenderte Webseiten, damit ihr Inhalt zum Erfassungszeitpunkt einsehbar bleibt.
- [Moli Web Research](https://github.com/assistifyai405/moli-webonderzoek) - Ein lokales MCP-Werkzeug in der Betaphase, das gespeicherte Webseiten-Snapshots vergleicht.
- [molisnap](https://github.com/7a6163/molisnap) - Rendert Single-Page-Apps vorab als HTML für Suchmaschinen-Crawler und KI-Bots.
- [PageSift](https://github.com/YOLOW92/pagesift) - Nutzt Moli als Fallback für iframe-Inhalte, die Lightpanda nicht erfasst.
- [Smart Tool](https://github.com/AllanSantos-DV/smart-tool-dist) - Greift für Coding-Agenten unter Windows auf Moli zurück, wenn eine HTTP-Anfrage den Seiteninhalt nicht liefert.
- [stvdy](https://github.com/jettapindika/stvdy) - Importiert Webseiten mit Moli als Lernmaterial, wenn Exa den Text nicht abrufen kann.
- [Vanilla](https://github.com/easylearnfromtw/vanilla) - Nach Isolierung des ausgehenden Netzwerkverkehrs lässt sich Moli für den Import öffentlicher Webseiten aktivieren.

<a id="agents-and-workspaces"></a>
<a id="agent-frameworks-and-workspaces"></a>

## Agenten-Frameworks und Arbeitsbereiche

- [A3S Code](https://github.com/A3S-Lab/Code) - Richtet für die Websuche von Coding-Agenten automatisch einen verifizierten Moli-Browser ein.
- [agent-fabric](https://github.com/BlueTeam-OU/agent-fabric) - Gibt jedem Coding-Agenten eine eigene temporäre Moli-Browsersitzung.
- [agnostic-router-kit](https://github.com/adelvillar1/agnostic-router-kit) - Nutzt zuerst den lokalen Moli-Browser, wenn ein Workflow eine JavaScript-Seite lesen soll.
- [AION](https://github.com/JayCRL/AION) - Bereitet mit Moli gelesene dynamische Webseiten als Karten im Arbeitsbereich des Agenten auf.
- [dsh-qq-bot](https://github.com/arrow1031-dev/dsh-qq-bot) - Ein QQ-Bot, der verlinkte Seiten bei Bedarf mit lokalem Moli als Markdown liest.
- [Internkim](https://github.com/yeomyeonggeori/internkim) - Ermöglicht dem KI-Assistenten eines Teams, mit lokalem Moli öffentliche Webseiten zu besuchen.
- [Lumen](https://github.com/Andrea17982/Lumen) - Liefert ein gemeinsames Moli-Browserwerkzeug für Desktop-Agenten wie Claude Code und Codex mit.
- [mem0-omp](https://github.com/millianlmx/mem0-omp) - Ermöglicht Coding-Agenten per Token den Zugriff auf einen Moli-Browser im Container.
- [Qianxun](https://github.com/imxood/qianxun) - Erkennt in der Desktop-Oberfläche für DeepSeek Harness die lokale Moli-Installation und ihre Version.
- [Relay](https://github.com/arcwright42/Relay) - Lässt Prompts auch dann absenden, wenn ein Seitenabruf mit Moli zu lange dauert.
- [Wick](https://github.com/yogasw/wick) - Lässt Go-Agenten Webseiten bei Bedarf mit lokalem Moli als Markdown lesen.

<a id="deployment-and-packaging"></a>
<a id="packaging-and-deployment"></a>

## Paketierung und Deployment

Installationsrezepte und Deployment-Vorlagen aus der Community.

- [1Panel App](https://github.com/skingko/1panel_app/tree/localApps/apps/x-moli) - Ein Community-Paket für die Bereitstellung von Moli über 1Panel.
- [A3S CLI](https://github.com/A3S-Lab/CLI) - Liefert die zur Zielplattform passende Moli-Laufzeitumgebung mit den A3S-Kommandozeilenwerkzeugen aus.
- [Homebrew Moli](https://github.com/hoishing/homebrew-moli) - Ein Homebrew-Tap der Community, der Moli und die passenden offiziellen Agenten-Skills installiert.
- [Lattice](https://github.com/mytecor/lattice/tree/main/profiles/moli) - Hostet Moli auf NixOS und ermöglicht die Ferninspektion von Webseiten mit DevTools.
- [moli-snap](https://github.com/sidalit/moli-snap) - Ein inoffizielles Linux-Snap, das Moli mit Schriftarten für Screenshots und PDFs bündelt.
- [orbsh/nixos](https://github.com/orbsh/nixos/blob/main/modules/system/units/moli.nix) - Legt Version und Prüfsumme von Moli für reproduzierbare NixOS-Installationen fest.
- [Railway Moli](https://github.com/two-workspaces/moli) - Stellt Moli auf Railway mit tokenbasiertem Fernzugriff auf den Browser bereit.

<a id="experimental-and-development-examples"></a>
<a id="development-examples-and-evaluations"></a>

## Entwicklungsbeispiele und Evaluierungen

Prototypen, Entwicklungsskripte und Evaluierungsberichte. Die genannten Testergebnisse stammen von den jeweiligen Autoren.

- [Aveli](https://github.com/pkmdev-sec/aveli) - Ein experimenteller Test prüft, ob der Browser-Agent eine Verbindung zum lokalen Moli aufbauen kann.
- [govio-map](https://github.com/chenxinma/govio-map) - Tippt mit Moli Zeichen in ein Einstellungsfeld und prüft, ob der Tastaturfokus erhalten bleibt.
- [Hydra Downloader](https://github.com/juanpimg/hydradownloader) - Prüft mit Moli, ob die Downloadseite bei verschiedenen Smartphone-Breiten über den Bildschirm hinausragt.
- [laravel-domains](https://github.com/yepbro/laravel-domains) - Vergleicht das Verhalten des Webcrawlers mit verschiedenen Moli-Versionen und mit Chromium.
- [llama.rs](https://github.com/yablokolabs/llama.rs) - Prüft mit Moli, ob die lokale WebAssembly-Chatdemo eine Frage beantwortet.
- [Master Maps](https://github.com/0bifthenelse/master-maps) - Führt End-to-End-Tests der 3D-Karte mit Moli aus und nutzt bei Bedarf das lokale Chromium.
- [Molifasi](https://github.com/A3S-Lab/Molifasi) - Ein Agenten-Prototyp, bei dem Apofasi die nächste Aktion auswählt und Moli sie im Browser ausführt.
- [ScopePay AI](https://github.com/yablokolabs/scopepay-ai) - Testet mit Moli, wie Käufer eine Zahlung in der PayPal-Sandbox freigeben.
- [SmartSpecPro](https://github.com/naibarn/SmartSpecPro) - Startet Moli ausschließlich für Linux-Abnahmetests ohne Root-Rechte.

## Mitwirken

Moli-Forks, Weiterentwicklungen und neue Einsatzmöglichkeiten sind willkommen. Wie du ein Projekt vorschlägst oder einen Eintrag verbesserst, steht in den [Beitragsrichtlinien](../CONTRIBUTING.md).

## Anmerkungen

Am **2026-11-19** wurden öffentlicher Quellcode und Projektdokumentation geprüft. Produktiveinsatz, Kundenbeziehungen und die unabhängige Bestätigung von Testergebnissen lagen außerhalb dieser Prüfung. Das [Prüfprotokoll](REVIEW.md) enthält Links zu den geprüften Versionen und den erfassten Belegen sowie Hinweise zu früheren Erwähnungen und nicht erreichbaren Repositories.
