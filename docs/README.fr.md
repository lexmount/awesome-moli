# Awesome Moli [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
  <a href="../README.md">English</a> | <a href="README.zh-CN.md">简体中文</a> | <a href="README.ja.md">日本語</a> | <a href="README.de.md">Deutsch</a> | <strong>Français</strong> | <a href="README.es.md">Español</a> | <a href="README.ko.md">한국어</a>
</p>

> Outils, intégrations et exemples pour [Moli](https://github.com/lexmount/moli), le navigateur sans interface open source pour les agents IA.

Découvrez Moli pour l’automatisation de navigateur, l’extraction web, les workflows d’agents et les services auto-hébergés. Certaines intégrations sont optionnelles ou expérimentales ; suivez le guide d’installation de chaque projet.

## Sommaire

- [Ressources officielles](#official-resources)
- [Outils de navigateur et MCP](#browser-tools-and-mcp)
- [Agents et espaces de travail](#agents-and-workspaces)
- [Extraction web et recherche](#web-extraction-and-research)
- [Tests et QA](#testing-and-qa)
- [Déploiement et paquets](#deployment-and-packaging)
- [Projets expérimentaux et exemples de développement](#experimental-and-development-examples)

<a id="official-resources"></a>

## Ressources officielles

- [Moli](https://github.com/lexmount/moli) - Dépôt officiel, instructions d’installation, utilisation de la CLI et documentation des protocoles d’automatisation.
- [Releases](https://github.com/lexmount/moli/releases) - Binaires précompilés et notes de version officielles.
- [Agent skills](https://github.com/lexmount/moli/tree/main/skills) - Skills officiels pour agents : récupération de pages, recherche web et lancement d’un serveur CDP.
- [WebMCP playground](https://github.com/lexmount/moli/tree/main/moli-playground/webmcp) - Scripts et démonstrations pour découvrir et appeler les outils WebMCP natifs d’un site avec Moli.
- [Webstone](https://github.com/lexmount/webstone) - Framework d’évaluation des navigateurs et outils web avec tâches reproductibles et preuves enregistrées.

<a id="browser-tools-and-mcp"></a>

## Outils de navigateur et MCP

- [Browser Bridge for Muse](https://github.com/rehantheorylab-pixel/browser-bridge-for-muse) - Passerelle d’automatisation de navigateur avec un moteur Moli optionnel piloté par Playwright via CDP.
- [chatctl](https://github.com/ironpark/toolz/tree/main/cli/chatctl) - CLI Go de gestion des sessions web de chat, avec Moli pour l’accès sans interface et Chrome pour la connexion interactive.
- [Delta Browser](https://github.com/DevAnimecx/deltabrowser) - Serveur de navigateur MCP avec moteur Moli géré et processus de travail isolés sous Linux x86_64.
- [dsh-moli](https://github.com/27painter/dsh-moli) - Plugin communautaire DeepSeek Harness pour l’extraction de pages, l’évaluation JavaScript, les captures d’écran, les PDF et le diagnostic du moteur.
- [Moli Job Apply](https://github.com/mcaupybugs/claude-job-apply-skill-moli) - Skill expérimental de recherche d’emploi qui remplit les formulaires avec Moli et demande une confirmation avant l’envoi.
- [Moli Web Research](https://github.com/assistifyai405/moli-webonderzoek) - Outils MCP locaux de recherche pour lire des URL choisies, conserver les sources et comparer des instantanés de pages ; actuellement en bêta.
- [Smart Tool](https://github.com/AllanSantos-DV/smart-tool-dist) - Distribution Windows d’outils pour agents utilisant Moli pour les pages JavaScript lorsque l’extraction HTTP ne suffit pas, avec repli sur Chromium.

<a id="agents-and-workspaces"></a>

## Agents et espaces de travail

- [A3S Code](https://github.com/A3S-Lab/Code) - Framework d’agents qui fournit un environnement Moli vérifié pour son moteur de recherche web sans interface.
- [agent-fabric](https://github.com/BlueTeam-OU/agent-fabric) - Plateforme de gestion d’agents de programmation utilisant Moli pour lire le web et Playwright MCP pour la navigation scriptée de chaque agent.
- [agnostic-router-kit](https://github.com/adelvillar1/agnostic-router-kit) - Boîte à outils de workflows d’agents qui rend les pages avec Moli en priorité, puis se replie sur Firecrawl auto-hébergé et HTTP.
- [AION](https://github.com/JayCRL/AION) - Infrastructure d’agents dont l’outil web.read utilise Moli pour renvoyer du Markdown rendu ou des données DOM structurées.
- [dsh-qq-bot](https://github.com/arrow1031-dev/dsh-qq-bot) - Intégration de bot QQ proposant un rendu local Moli optionnel pour son outil qq_webfetch.
- [Internkim](https://github.com/yeomyeonggeori/internkim) - Espace de travail d’agents en équipe avec un navigateur Moli pour consulter les pages publiques.
- [Lumen](https://github.com/Andrea17982/Lumen) - Espace de travail de bureau pour agents qui embarque Moli et partage les outils de navigation entre plusieurs adaptateurs de modèles et de CLI.
- [mem0-omp](https://github.com/millianlmx/mem0-omp) - Environnement d’exécution d’agents de programmation avec navigateurs Moli conteneurisés et passerelle CDP HTTP/WebSocket authentifiée.
- [Qianxun](https://github.com/imxood/qianxun) - Espace de travail de bureau Tauri pour DeepSeek Harness avec détection des exécutables Moli locaux et vérification des versions.
- [Relay](https://github.com/arcwright42/Relay) - Environnement d’agents avec récupération de pages Moli limitée en durée et en volume, et installation gérée du navigateur.
- [Wick](https://github.com/yogasw/wick) - Hôte d’agents en Go avec connecteur de navigateur Moli optionnel, sessions CDP et extraction Markdown.

<a id="web-extraction-and-research"></a>

## Extraction web et recherche

- [888-url2md](https://github.com/tbdavid2019/888-url2md) - Service de conversion de pages en Markdown avec moteur CDP Moli local et politique distincte de repli sur Chrome.
- [A3S Search](https://github.com/A3S-Lab/Search) - Moteur de recherche intégrable avec rendu par la CLI Moli et limitation du nombre de rendus simultanés.
- [Brains](https://github.com/YuniqueUnic/brains) - Base de connaissances Markdown versionnée avec rendu Moli optionnel lors de l’importation d’URL.
- [CTI Expert](https://github.com/7onez/cti-expert) - Boîte à outils de renseignement sur les menaces utilisant Moli pour extraire le DOM après exécution JavaScript et Chromium pour les preuves visuelles.
- [HEIS](https://github.com/u4399com-beep/heis) - Système de collecte de romans avec une passerelle HTTP en Go pour la récupération de pages et l’évaluation de scripts par Moli.
- [hermes-dev](https://github.com/Sucotasch/hermes-dev) - Outils de recherche Hermes ajoutant le rendu Moli à la chaîne de repli pour la lecture de pages.
- [Lens](https://github.com/bysages/lens) - Boîte à outils web TypeScript utilisant Moli via CDP pour les captures d’écran et la lecture de pages.
- [ModalPrism](https://github.com/MistLoom/ModalPrism) - Système de collecte de données en Rust dont l’adaptateur de navigateur rend les pages dynamiques avec la CLI Moli.
- [molisnap](https://github.com/7a6163/molisnap) - Service de prérendu de SPA pour les robots des moteurs de recherche et d’IA, avec cache et préchargement depuis un sitemap.
- [PageSift](https://github.com/YOLOW92/pagesift) - Service Rust d’extraction web et documentaire intégrant Moli dans une chaîne de sélection Lightpanda, Moli et Chrome.
- [stvdy](https://github.com/jettapindika/stvdy) - Espace d’étude qui importe des sources web via une chaîne de repli Exa, Moli et HTTP/readability.
- [Vanilla](https://github.com/easylearnfromtw/vanilla) - Espace IA familial avec adaptateur d’extraction Moli à activer explicitement, nécessitant une isolation réseau sortante configurée séparément.

<a id="testing-and-qa"></a>

## Tests et QA

- [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - Framework de tests de bout en bout avec helper Moli expérimental, gestion des processus locaux et connexion aux points d’accès CDP existants.
- [KMJ CodeBridge](https://github.com/kmjtechno/kmj-codebridge) - Outils de développement MCP avec contrôles d’extraction Moli optionnels sur des pages publiques fixes et repli sur Chrome pour la QA visuelle.

<a id="deployment-and-packaging"></a>

## Déploiement et paquets

Recettes d’installation et modèles de déploiement communautaires.

- [1Panel App](https://github.com/skingko/1panel_app/tree/localApps/apps/x-moli) - Recette communautaire d’application 1Panel et construction d’image Docker pour Moli.
- [A3S CLI](https://github.com/A3S-Lab/CLI) - Distribution en ligne de commande A3S embarquant un environnement Moli adapté à chaque plateforme cible.
- [Homebrew Moli](https://github.com/hoishing/homebrew-moli) - Tap Homebrew communautaire installant les binaires Moli et les skills officiels d’agents de la même version.
- [Lattice](https://github.com/mytecor/lattice/tree/main/profiles/moli) - Service Moli pour NixOS avec accès CDP distant, DevTools hébergés et accès via Caddy/Authentik.
- [moli-snap](https://github.com/sidalit/moli-snap) - Paquet Snap non officiel pour exécuter la CLI Moli et le serveur d’automatisation sous Linux.
- [orbsh/nixos](https://github.com/orbsh/nixos/blob/main/modules/system/units/moli.nix) - Définition de paquet NixOS pour des binaires Moli à version fixée et leurs dépendances d’exécution.
- [Railway Moli](https://github.com/two-workspaces/moli) - Modèle de déploiement Railway avec passerelle Caddy protégée par jeton et réécriture des adresses WebSocket publiques.

<a id="experimental-and-development-examples"></a>

## Projets expérimentaux et exemples de développement

Prototypes, scripts de développement et rapports d’évaluation. Les résultats de tests sont ceux rapportés par leurs auteurs.

- [Aveli](https://github.com/pkmdev-sec/aveli) - Environnement Moli expérimental et sondes de compatibilité pour un agent navigateur.
- [govio-map](https://github.com/chenxinma/govio-map) - Script de test rapide CDP vérifiant le focus des champs et la validation dans la boîte de dialogue des paramètres d’une application.
- [Hydra Downloader](https://github.com/juanpimg/hydradownloader) - Scripts de développement utilisant Moli CDP pour vérifier la mise en page adaptative et les parcours de téléchargement.
- [laravel-domains](https://github.com/yepbro/laravel-domains) - Projet de crawler documentant les évaluations de Moli par version, les régressions, les nouveaux tests et les comparaisons avec Chromium.
- [llama.rs](https://github.com/yablokolabs/llama.rs) - Script de test navigateur utilisant Moli pour exercer l’interface JavaScript d’une application de chat Rust/WASM.
- [Master Maps](https://github.com/0bifthenelse/master-maps) - Application cartographique avec scripts de bout en bout pilotés par Moli et repli explicite sur Chromium local.
- [Molifasi](https://github.com/A3S-Lab/Molifasi) - Prototype Rust d’agent navigateur combinant les observations et actions CDP de Moli avec les décisions d’Apofasi.
- [ScopePay AI](https://github.com/yablokolabs/scopepay-ai) - Exemple de paiement dans le bac à sable PayPal utilisant Moli CDP pour le parcours d’approbation de l’acheteur.
- [SmartSpecPro](https://github.com/naibarn/SmartSpecPro) - Lanceur de tests d’acceptation Moli sous Linux sans privilèges root, exclu des compilations par défaut.

## Contribuer

Ajoutez un projet Moli utile ou améliorez une description par Pull Request. Consultez le [guide de contribution](../CONTRIBUTING.md) pour les critères d’inclusion et les mises à jour des traductions.

## Notes

Vérification des sources : **2026-11-19**. Le [journal de vérification](REVIEW.md) et l’[instantané des preuves](../data/review-2026-11-19.json) contiennent les sources à version fixée, les mentions historiques et les dépôts inaccessibles. L’inclusion documente une intégration ou un exemple public ; elle ne prouve ni un usage en production, ni une relation client, ni une reproduction indépendante des tests.
