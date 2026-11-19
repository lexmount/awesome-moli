# Awesome Moli [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
  <a href="../README.md">English</a> | <a href="README.zh-CN.md">简体中文</a> | <a href="README.ja.md">日本語</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <strong>Español</strong> | <a href="README.ko.md">한국어</a>
</p>

> Herramientas, integraciones y ejemplos para [Moli](https://github.com/lexmount/moli), el navegador sin interfaz de código abierto para agentes de IA.

Descubre Moli para la automatización de navegadores, la extracción web, los flujos de agentes y los servicios autoalojados. Algunas integraciones son opcionales o experimentales; consulta la guía de configuración de cada proyecto.

## Contenido

- [Recursos oficiales](#official-resources)
- [Herramientas de navegador y MCP](#browser-tools-and-mcp)
- [Agentes y espacios de trabajo](#agents-and-workspaces)
- [Extracción web e investigación](#web-extraction-and-research)
- [Pruebas y QA](#testing-and-qa)
- [Despliegue y paquetes](#deployment-and-packaging)
- [Proyectos experimentales y ejemplos de desarrollo](#experimental-and-development-examples)

<a id="official-resources"></a>

## Recursos oficiales

- [Moli](https://github.com/lexmount/moli) - Repositorio oficial, instrucciones de instalación, uso de la CLI y documentación de protocolos de automatización.
- [Releases](https://github.com/lexmount/moli/releases) - Binarios precompilados y notas oficiales de las versiones.
- [Agent skills](https://github.com/lexmount/moli/tree/main/skills) - Skills oficiales para agentes: obtención de páginas, búsqueda web y ejecución de un servidor CDP.
- [WebMCP playground](https://github.com/lexmount/moli/tree/main/moli-playground/webmcp) - Scripts y demostraciones para descubrir e invocar las herramientas WebMCP nativas de un sitio mediante Moli.
- [Webstone](https://github.com/lexmount/webstone) - Framework de evaluación de navegadores y herramientas web con tareas reproducibles y evidencias registradas.

<a id="browser-tools-and-mcp"></a>

## Herramientas de navegador y MCP

- [Browser Bridge for Muse](https://github.com/rehantheorylab-pixel/browser-bridge-for-muse) - Puente de automatización de navegadores con un motor Moli opcional controlado mediante Playwright y CDP.
- [chatctl](https://github.com/ironpark/toolz/tree/main/cli/chatctl) - CLI en Go para gestionar sesiones web de chat, con Moli para el acceso sin interfaz y Chrome para el inicio de sesión interactivo.
- [Delta Browser](https://github.com/DevAnimecx/deltabrowser) - Servidor de navegador MCP con motor Moli gestionado y procesos aislados en Linux x86_64.
- [dsh-moli](https://github.com/27painter/dsh-moli) - Plugin comunitario de DeepSeek Harness para extraer páginas, evaluar JavaScript, generar capturas y PDF, y diagnosticar el motor.
- [Moli Job Apply](https://github.com/mcaupybugs/claude-job-apply-skill-moli) - Skill experimental de búsqueda de empleo que rellena formularios con Moli y pide confirmación antes de enviarlos.
- [Moli Web Research](https://github.com/assistifyai405/moli-webonderzoek) - Herramientas MCP locales de investigación para leer URL seleccionadas, conservar fuentes y comparar instantáneas de páginas; actualmente en beta.
- [Smart Tool](https://github.com/AllanSantos-DV/smart-tool-dist) - Distribución de herramientas para agentes en Windows que usa Moli en páginas JavaScript cuando la extracción HTTP no basta, con Chromium como alternativa.

<a id="agents-and-workspaces"></a>

## Agentes y espacios de trabajo

- [A3S Code](https://github.com/A3S-Lab/Code) - Framework de agentes que prepara un entorno de ejecución Moli verificado para su motor de búsqueda web sin interfaz.
- [agent-fabric](https://github.com/BlueTeam-OU/agent-fabric) - Plataforma de gestión de agentes de programación que usa Moli para leer la web y Playwright MCP para la navegación programada de cada agente.
- [agnostic-router-kit](https://github.com/adelvillar1/agnostic-router-kit) - Herramientas de flujos de trabajo para agentes que renderizan primero con Moli y recurren después a Firecrawl autoalojado y HTTP.
- [AION](https://github.com/JayCRL/AION) - Infraestructura de agentes cuya herramienta web.read usa Moli para devolver Markdown renderizado o datos DOM estructurados.
- [dsh-qq-bot](https://github.com/arrow1031-dev/dsh-qq-bot) - Integración de bot QQ con renderizado local Moli opcional para la herramienta qq_webfetch.
- [Internkim](https://github.com/yeomyeonggeori/internkim) - Espacio de trabajo de agentes para equipos con un navegador Moli para visitar páginas públicas.
- [Lumen](https://github.com/Andrea17982/Lumen) - Espacio de trabajo de escritorio para agentes que incluye Moli y comparte herramientas de navegador entre varios adaptadores de modelos y CLI.
- [mem0-omp](https://github.com/millianlmx/mem0-omp) - Entorno de ejecución de agentes de programación con navegadores Moli en contenedores y una pasarela CDP HTTP/WebSocket con autenticación.
- [Qianxun](https://github.com/imxood/qianxun) - Entorno de escritorio Tauri para DeepSeek Harness con detección de ejecutables Moli locales y comprobación de versiones.
- [Relay](https://github.com/arcwright42/Relay) - Entorno de agentes con obtención de páginas mediante Moli limitada en tiempo y volumen, e instalación gestionada del navegador.
- [Wick](https://github.com/yogasw/wick) - Host de agentes en Go con conector de navegador Moli opcional, sesiones CDP y extracción de Markdown.

<a id="web-extraction-and-research"></a>

## Extracción web e investigación

- [888-url2md](https://github.com/tbdavid2019/888-url2md) - Servicio de conversión de páginas a Markdown con un motor CDP Moli local y una política separada de uso alternativo de Chrome.
- [A3S Search](https://github.com/A3S-Lab/Search) - Motor de búsqueda integrable con renderizador CLI de Moli y límite de renderizados simultáneos.
- [Brains](https://github.com/YuniqueUnic/brains) - Almacén de conocimiento Markdown con control de versiones y renderizado Moli opcional al importar URL.
- [CTI Expert](https://github.com/7onez/cti-expert) - Herramientas de inteligencia de amenazas que usan Moli para extraer el DOM tras ejecutar JavaScript y mantienen Chromium para la evidencia visual.
- [HEIS](https://github.com/u4399com-beep/heis) - Sistema de recopilación de novelas con un puente HTTP en Go para obtener páginas y evaluar scripts mediante Moli.
- [hermes-dev](https://github.com/Sucotasch/hermes-dev) - Herramientas de investigación de Hermes que añaden el renderizado Moli a la cadena de alternativas para leer páginas.
- [Lens](https://github.com/bysages/lens) - Herramientas web en TypeScript que usan Moli mediante CDP para capturas de pantalla y lectura de páginas.
- [ModalPrism](https://github.com/MistLoom/ModalPrism) - Sistema de recopilación de datos en Rust cuyo adaptador de navegador renderiza páginas dinámicas mediante la CLI de Moli.
- [molisnap](https://github.com/7a6163/molisnap) - Servicio de prerenderizado de SPA para rastreadores de búsqueda y bots de IA, con caché y precarga desde sitemaps.
- [PageSift](https://github.com/YOLOW92/pagesift) - Servicio de extracción web y documental en Rust que integra Moli en una cadena de selección Lightpanda, Moli y Chrome.
- [stvdy](https://github.com/jettapindika/stvdy) - Espacio de estudio que importa fuentes web mediante una cadena de alternativas Exa, Moli y HTTP/readability.
- [Vanilla](https://github.com/easylearnfromtw/vanilla) - Espacio de IA familiar con adaptador de extracción Moli que requiere activación explícita y aislamiento de red saliente configurado por separado.

<a id="testing-and-qa"></a>

## Pruebas y QA

- [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - Framework de pruebas de extremo a extremo con helper Moli experimental, gestión de procesos locales y conexión a endpoints CDP existentes.
- [KMJ CodeBridge](https://github.com/kmjtechno/kmj-codebridge) - Herramientas de desarrollo MCP con comprobaciones opcionales de extracción Moli para páginas públicas fijas y Chrome como alternativa para QA visual.

<a id="deployment-and-packaging"></a>

## Despliegue y paquetes

Recetas de instalación y plantillas de despliegue de la comunidad.

- [1Panel App](https://github.com/skingko/1panel_app/tree/localApps/apps/x-moli) - Receta comunitaria de aplicación 1Panel y compilación de imagen Docker para Moli.
- [A3S CLI](https://github.com/A3S-Lab/CLI) - Distribución de línea de comandos A3S con un entorno de ejecución Moli incluido para cada plataforma de destino.
- [Homebrew Moli](https://github.com/hoishing/homebrew-moli) - Tap comunitario de Homebrew que instala los binarios de Moli y los skills oficiales para agentes de la misma versión.
- [Lattice](https://github.com/mytecor/lattice/tree/main/profiles/moli) - Servicio Moli en NixOS con acceso CDP remoto, DevTools alojadas y entrada mediante Caddy/Authentik.
- [moli-snap](https://github.com/sidalit/moli-snap) - Paquete Snap no oficial para ejecutar la CLI de Moli y su servidor de automatización en Linux.
- [orbsh/nixos](https://github.com/orbsh/nixos/blob/main/modules/system/units/moli.nix) - Definición de paquete NixOS para binarios de versiones fijadas de Moli y sus dependencias de ejecución.
- [Railway Moli](https://github.com/two-workspaces/moli) - Plantilla de despliegue en Railway con pasarela Caddy protegida por token y reescritura de endpoints WebSocket públicos.

<a id="experimental-and-development-examples"></a>

## Proyectos experimentales y ejemplos de desarrollo

Prototipos, scripts de desarrollo e informes de evaluación. Los resultados de las pruebas proceden de sus autores.

- [Aveli](https://github.com/pkmdev-sec/aveli) - Entorno Moli experimental y pruebas de compatibilidad para un agente de navegador.
- [govio-map](https://github.com/chenxinma/govio-map) - Script de prueba rápida CDP que comprueba el foco de entrada y la validación en el diálogo de ajustes de una aplicación.
- [Hydra Downloader](https://github.com/juanpimg/hydradownloader) - Scripts de desarrollo que usan Moli CDP para comprobar diseños adaptables y flujos de descarga.
- [laravel-domains](https://github.com/yepbro/laravel-domains) - Proyecto de rastreo que documenta evaluaciones de Moli por versión, regresiones, nuevas pruebas y comparaciones con Chromium.
- [llama.rs](https://github.com/yablokolabs/llama.rs) - Script de prueba de navegador que usa Moli para ejercitar la interfaz JavaScript de una aplicación de chat Rust/WASM.
- [Master Maps](https://github.com/0bifthenelse/master-maps) - Aplicación de mapas con scripts de extremo a extremo basados en Moli y alternativa explícita a Chromium local.
- [Molifasi](https://github.com/A3S-Lab/Molifasi) - Prototipo de agente de navegador en Rust que combina observaciones y acciones CDP de Moli con decisiones de Apofasi.
- [ScopePay AI](https://github.com/yablokolabs/scopepay-ai) - Ejemplo de pago en el entorno de pruebas de PayPal que usa Moli CDP para el flujo de aprobación del comprador.
- [SmartSpecPro](https://github.com/naibarn/SmartSpecPro) - Lanzador de pruebas de aceptación de Moli en Linux sin privilegios root, excluido de las compilaciones predeterminadas.

## Contribuir

Añade un proyecto Moli útil o mejora una descripción mediante un Pull Request. Consulta la [guía de contribución](../CONTRIBUTING.md) para los criterios de inclusión y las actualizaciones de traducciones.

## Notas

Revisión de fuentes: **2026-11-19**. El [registro de revisión](REVIEW.md) y la [instantánea de evidencias](../data/review-2026-11-19.json) incluyen fuentes fijadas a versiones, menciones históricas y repositorios inaccesibles. La inclusión documenta una integración o un ejemplo público; no demuestra uso en producción, condición de cliente ni reproducción independiente de las pruebas.
