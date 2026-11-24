<h1 align="center">Awesome Moli</h1>

<p align="center">
  <a href="../README.md">English</a> | <a href="README.zh-CN.md">简体中文</a> | <a href="README.ja.md">日本語</a> | <a href="README.de.md">Deutsch</a> | <strong>Français</strong> | <a href="README.es.md">Español</a> | <a href="README.ko.md">한국어</a>
</p>

> [Moli](https://github.com/lexmount/moli) est un navigateur open source sans interface graphique conçu pour les agents d’IA. Cette liste réunit des projets qui utilisent, étendent ou distribuent Moli, notamment des outils d’automatisation du navigateur, des intégrations de frameworks, des projets dérivés, des solutions de déploiement et des exemples de développement.

## Sommaire

- [Forks et projets dérivés](#forks-and-derivatives)
- [Outils de test et d’assurance qualité](#testing-and-qa-tools)
- [Automatisation du navigateur et flux de travail](#browser-automation-and-workflows)
- [Serveurs MCP](#mcp-servers)
- [Rendu et extraction web](#web-rendering-and-extraction)
- [Frameworks et espaces de travail pour agents](#agent-frameworks-and-workspaces)
- [Création de paquets et déploiement](#packaging-and-deployment)
- [Exemples de développement et évaluations](#development-examples-and-evaluations)

<a id="forks-and-derivatives"></a>

## Forks et projets dérivés

- **[Limo](https://github.com/Spxg/limo) - Exécute du JavaScript dans le terminal avec toutes les API web du navigateur Moli.**
- [moli-stealth](https://github.com/Stravia-AI/moli-stealth) - Applique aux connexions HTTP et WebSocket de Moli un profil réseau inspiré de Chrome.
- [pilot](https://github.com/WSAdam/pilot) - Affiche en direct dans une fenêtre la navigation d’un agent piloté par Playwright MCP.

<a id="testing-and-qa"></a>
<a id="testing-and-qa-tools"></a>

## Outils de test et d’assurance qualité

- [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - Exécute des tests de bout en bout avec un moteur Moli expérimental.
- **[e2e](https://github.com/e2e-inc/e2e) - Teste en langage naturel des parcours comme le paiement dans Moli et rejoue les actions vérifiées sans nouvel appel au modèle.**
- [KMJ CodeBridge](https://github.com/kmjtechno/kmj-codebridge) - Peut vérifier avec Moli si le texte de pages de test publiques prédéfinies est lisible.

<a id="browser-tools-and-mcp"></a>
<a id="browser-automation-and-workflows"></a>

## Automatisation du navigateur et flux de travail

- [Browser Bridge for Muse](https://github.com/rehantheorylab-pixel/browser-bridge-for-muse) - Permet à Muse de choisir Moli comme navigateur local pour Playwright.
- [chatctl](https://github.com/ironpark/toolz/tree/main/cli/chatctl) - Réutilise votre session Chrome pour lire vos conversations dans le terminal avec Moli.
- [Delta Browser](https://github.com/DevAnimecx/deltabrowser) - Exécute les sessions de navigation MCP dans des processus Moli isolés sous Linux x86_64.
- **[dsh-moli](https://github.com/27painter/dsh-moli) - S’appuie sur le moteur Moli, installé séparément, pour fournir des outils de navigation à DeepSeek Harness, Codex et OpenCode.**
- [Moli Job Apply](https://github.com/mcaupybugs/claude-job-apply-skill-moli) - Cet assistant expérimental remplit les formulaires de candidature et demande votre accord avant l’envoi.
- [sessfork](https://github.com/wasabihu/sessfork) - Duplique en une commande votre session Chrome authentifiée dans le navigateur sans interface d’un agent IA en arrière-plan, sans verrouiller le profil local.

<a id="mcp-servers"></a>

## Serveurs MCP

Des serveurs MCP qui exposent Moli sur le protocole que les agents parlent déjà : le navigateur reste local et est piloté directement par son pipe DevTools, sans wrapper Node.js.

- **[sessfork-mcp](https://github.com/wasabihu/sessfork/tree/main/rust/sessfork-mcp) - Le serveur MCP natif en Rust du projet sessfork cité plus haut : il lance Moli et communique directement avec le pipe remote-debugging, sans runtime Node.js.**

<a id="web-extraction-and-research"></a>
<a id="web-rendering-and-extraction"></a>

## Rendu et extraction web

- [888-url2md](https://github.com/tbdavid2019/888-url2md) - Convertit des pages web en Markdown par lots et utilise Moli pour celles qui nécessitent JavaScript.
- [A3S Search](https://github.com/A3S-Lab/Search) - Utilise Moli pour lire les pages des résultats de recherche qui nécessitent JavaScript.
- [Brains](https://github.com/YuniqueUnic/brains) - Peut importer des pages dynamiques avec Moli sous forme de notes Markdown avec historique des versions.
- **[CTI Expert](https://github.com/7onez/cti-expert) - Recueille avec Moli le contenu chargé par JavaScript pour les enquêtes sur les cybermenaces. [Installer Moli (section 4)](https://github.com/7onez/cti-expert/blob/main/scripts/platform-setup.md#4-fastest-path--run-the-bundled-installer-once)**
- [HEIS](https://github.com/u4399com-beep/heis) - Peut utiliser Moli pour recueillir les chapitres de romans en ligne chargés dynamiquement.
- [hermes-dev](https://github.com/Sucotasch/hermes-dev#4-deepseek-harness-bridge-agents-own-web-tooling) - `mfetch` lit les pages en Markdown directement avec Moli et `render` l’appelle si le rendu nécessite un navigateur, avec un repli possible sur HTTP dans les deux cas.
- [Lens](https://github.com/bysages/lens) - Expose une API HTTP pour réaliser des captures de pages web avec Moli.
- [ModalPrism](https://github.com/MistLoom/ModalPrism) - Archive les pages dynamiques rendues par Moli pour pouvoir les relire telles qu’elles ont été collectées.
- [Moli Web Research](https://github.com/assistifyai405/moli-webonderzoek) - Cet outil MCP local en bêta compare des instantanés de pages web enregistrés à différentes dates.
- [molisnap](https://github.com/7a6163/molisnap) - Prégénère le HTML des applications monopages pour les robots de recherche et les agents IA.
- [PageSift](https://github.com/YOLOW92/pagesift) - Fait appel à Moli pour lire le contenu des iframes qui échappe à Lightpanda.
- [Smart Tool](https://github.com/AllanSantos-DV/smart-tool-dist) - Utilise Moli pour les agents de développement sous Windows quand HTTP seul ne suffit pas.
- [stvdy](https://github.com/jettapindika/stvdy) - Importe des pages comme supports d’étude avec Moli quand Exa ne trouve pas le texte.
- [Vanilla](https://github.com/easylearnfromtw/vanilla) - Permet d’activer Moli pour importer des pages publiques après isolation du trafic sortant.

<a id="agents-and-workspaces"></a>
<a id="agent-frameworks-and-workspaces"></a>

## Frameworks et espaces de travail pour agents

- [A3S Code](https://github.com/A3S-Lab/Code) - Installe automatiquement une version vérifiée de Moli pour les recherches web des agents de développement.
- [agent-fabric](https://github.com/BlueTeam-OU/agent-fabric) - Fournit à chaque agent de développement sa propre session de navigation temporaire avec Moli.
- [agnostic-router-kit](https://github.com/adelvillar1/agnostic-router-kit) - Utilise en priorité Moli en local lorsqu’un workflow doit lire une page JavaScript.
- [AION](https://github.com/JayCRL/AION) - Affiche les pages dynamiques lues avec Moli sous forme de fiches dans l’espace de travail de l’agent.
- [dsh-qq-bot](https://github.com/arrow1031-dev/dsh-qq-bot) - Ce bot QQ peut lire les liens partagés en Markdown avec Moli en local.
- [Internkim](https://github.com/yeomyeonggeori/internkim) - Permet à l’assistant IA d’une équipe de parcourir des pages publiques avec Moli en local.
- [Lumen](https://github.com/Andrea17982/Lumen) - Intègre un outil de navigation Moli partagé sur le bureau par Claude Code, Codex et d’autres agents.
- [mem0-omp](https://github.com/millianlmx/mem0-omp) - Donne aux agents de développement un accès par jeton à un navigateur Moli en conteneur.
- [Qianxun](https://github.com/imxood/qianxun) - Détecte la version locale de Moli dans une application de bureau pour DeepSeek Harness.
- [Relay](https://github.com/arcwright42/Relay) - Permet d’envoyer sa requête même si Moli dépasse le délai de lecture d’une page.
- [Wick](https://github.com/yogasw/wick) - Permet aux agents Go de lire des pages en Markdown avec un navigateur Moli local en option.

<a id="deployment-and-packaging"></a>
<a id="packaging-and-deployment"></a>

## Création de paquets et déploiement

Recettes d’installation et modèles de déploiement communautaires.

- [1Panel App](https://github.com/skingko/1panel_app/tree/localApps/apps/x-moli) - Ce paquet communautaire permet de déployer Moli depuis 1Panel.
- [A3S CLI](https://github.com/A3S-Lab/CLI) - Distribue la version de Moli adaptée à la plateforme avec les outils en ligne de commande A3S.
- [Homebrew Moli](https://github.com/hoishing/homebrew-moli) - Ce dépôt Homebrew communautaire installe Moli et les compétences officielles pour agents correspondant à sa version.
- [Lattice](https://github.com/mytecor/lattice/tree/main/profiles/moli) - Héberge Moli sous NixOS pour déboguer des pages à distance avec DevTools.
- [moli-snap](https://github.com/sidalit/moli-snap) - Ce paquet Snap non officiel pour Linux fournit Moli avec des polices pour les captures d’écran et les PDF.
- [orbsh/nixos](https://github.com/orbsh/nixos/blob/main/modules/system/units/moli.nix) - Fixe la version et la somme de contrôle de Moli pour des installations NixOS reproductibles.
- [Railway Moli](https://railway.com/deploy/moli?referralCode=sLjDXb) - Déploie Moli sur Railway avec un accès distant au navigateur protégé par jeton.

<a id="experimental-and-development-examples"></a>
<a id="development-examples-and-evaluations"></a>

## Exemples de développement et évaluations

Prototypes, scripts de développement et rapports d’évaluation. Les résultats de tests sont ceux rapportés par leurs auteurs.

- [Aveli](https://github.com/pkmdev-sec/aveli) - Un test expérimental vérifie la connexion de l’agent de navigation à Moli en local.
- [govio-map](https://github.com/chenxinma/govio-map) - Saisit du texte avec Moli pour vérifier qu’un champ des paramètres garde le focus à chaque frappe.
- [Hydra Downloader](https://github.com/juanpimg/hydradownloader) - Vérifie avec Moli si la page de téléchargement déborde sur différentes largeurs d’écran mobile.
- [laravel-domains](https://github.com/yepbro/laravel-domains) - Compare le comportement de son robot de collecte avec plusieurs versions de Moli et avec Chromium.
- [llama.rs](https://github.com/yablokolabs/llama.rs) - Vérifie avec Moli que sa démo de chat WebAssembly en local répond à une question.
- [Master Maps](https://github.com/0bifthenelse/master-maps) - Teste sa carte 3D de bout en bout avec Moli et peut se rabattre sur Chromium en local.
- [Molifasi](https://github.com/A3S-Lab/Molifasi) - Cet agent prototype laisse Apofasi choisir l’action que Moli exécutera sur la page.
- [ScopePay AI](https://github.com/yablokolabs/scopepay-ai) - Teste avec Moli l’approbation du paiement par l’acheteur dans le bac à sable PayPal.
- [SmartSpecPro](https://github.com/naibarn/SmartSpecPro) - Lance Moli uniquement pour les tests de recette sous Linux sans privilèges root.

## Contribuer

Les forks de Moli, les projets dérivés et les nouveaux usages sont les bienvenus. Pour proposer un projet ou améliorer une description, consultez le [guide de contribution](../CONTRIBUTING.md).

## Notes

La première vérification du code et de la documentation publics a eu lieu le **2026-11-19**. L’usage en production, les relations commerciales et la reproduction indépendante des tests sortent du cadre de cette vérification. Le [journal de vérification](REVIEW.md) rassemble les liens vers les révisions consultées, les relevés de sources, les mentions historiques et les dépôts inaccessibles.
