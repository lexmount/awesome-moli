<h1 align="center">Awesome Moli</h1>

<p align="center">
  <a href="../README.md">English</a> | <a href="README.zh-CN.md">简体中文</a> | <a href="README.ja.md">日本語</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <strong>Español</strong> | <a href="README.ko.md">한국어</a>
</p>

> [Moli](https://github.com/lexmount/moli) es un navegador de código abierto sin interfaz gráfica para agentes de IA. Esta lista reúne proyectos que usan, amplían o distribuyen Moli, entre ellos herramientas de automatización del navegador, integraciones con frameworks, proyectos derivados, opciones de despliegue y ejemplos de desarrollo.

## Contenido

- [Forks y proyectos derivados](#forks-and-derivatives)
- [Herramientas de pruebas y QA](#testing-and-qa-tools)
- [Automatización del navegador y flujos de trabajo](#browser-automation-and-workflows)
- [Renderizado y extracción web](#web-rendering-and-extraction)
- [Frameworks y espacios de trabajo para agentes](#agent-frameworks-and-workspaces)
- [Empaquetado y despliegue](#packaging-and-deployment)
- [Ejemplos de desarrollo y evaluaciones](#development-examples-and-evaluations)

<a id="forks-and-derivatives"></a>

## Forks y proyectos derivados

- **[Limo](https://github.com/Spxg/limo) - Ejecuta JavaScript en la terminal con todas las API web del navegador Moli.**
- [moli-stealth](https://github.com/Stravia-AI/moli-stealth) - Aplica a las conexiones HTTP y WebSocket de Moli un perfil de red similar al de Chrome.
- [pilot](https://github.com/WSAdam/pilot) - Muestra en una ventana cómo navega en tiempo real un agente con Playwright MCP.

<a id="testing-and-qa"></a>
<a id="testing-and-qa-tools"></a>

## Herramientas de pruebas y QA

- [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - Ejecuta pruebas de extremo a extremo con un motor experimental basado en Moli.
- **[e2e](https://github.com/e2e-inc/e2e) - Prueba en Moli flujos como el pago con instrucciones en lenguaje natural y repite las acciones verificadas sin volver a llamar al modelo.**
- [KMJ CodeBridge](https://github.com/kmjtechno/kmj-codebridge) - Puede comprobar con Moli si se extrae el texto de páginas públicas de prueba predefinidas.

<a id="browser-tools-and-mcp"></a>
<a id="browser-automation-and-workflows"></a>

## Automatización del navegador y flujos de trabajo

- [Browser Bridge for Muse](https://github.com/rehantheorylab-pixel/browser-bridge-for-muse) - Permite a Muse elegir Moli como navegador local para Playwright.
- [chatctl](https://github.com/ironpark/toolz/tree/main/cli/chatctl) - Reutiliza tu sesión de Chrome para leer conversaciones en la terminal con Moli.
- [Delta Browser](https://github.com/DevAnimecx/deltabrowser) - Ejecuta sesiones de navegador MCP en procesos aislados de Moli en Linux x86_64.
- **[dsh-moli](https://github.com/27painter/dsh-moli) - Herramientas de navegación basadas en el motor Moli para DeepSeek Harness, Codex y OpenCode (el motor se instala por separado).**
- [Moli Job Apply](https://github.com/mcaupybugs/claude-job-apply-skill-moli) - Este asistente experimental rellena solicitudes de empleo y pide confirmación antes de enviarlas.
- [sessfork](https://github.com/wasabihu/sessfork) - En macOS y Linux, un agente de IA puede usar Moli en segundo plano para visitar sitios donde ya has iniciado sesión en Chrome.

<a id="web-extraction-and-research"></a>
<a id="web-rendering-and-extraction"></a>

## Renderizado y extracción web

- [888-url2md](https://github.com/tbdavid2019/888-url2md) - Convierte páginas web a Markdown por lotes y usa Moli para las que requieren JavaScript.
- [A3S Search](https://github.com/A3S-Lab/Search) - Usa Moli para leer las páginas de los resultados de búsqueda que necesitan JavaScript.
- [Brains](https://github.com/YuniqueUnic/brains) - Permite importar páginas dinámicas con Moli como notas Markdown con historial de versiones.
- **[CTI Expert](https://github.com/7onez/cti-expert) - Recopila con Moli contenido web cargado por JavaScript para investigar ciberamenazas. [Instalar Moli (sección 4)](https://github.com/7onez/cti-expert/blob/main/scripts/platform-setup.md#4-fastest-path--run-the-bundled-installer-once)**
- [HEIS](https://github.com/u4399com-beep/heis) - Puede usar Moli para recopilar capítulos de novelas en línea que se cargan dinámicamente.
- [hermes-dev](https://github.com/Sucotasch/hermes-dev#4-deepseek-harness-bridge-agents-own-web-tooling) - `mfetch` lee páginas en Markdown directamente con Moli y `render` lo usa cuando hace falta un navegador, con HTTP como alternativa para ambos.
- [Lens](https://github.com/bysages/lens) - Ofrece una API HTTP para hacer capturas de páginas web con Moli.
- [ModalPrism](https://github.com/MistLoom/ModalPrism) - Archiva páginas dinámicas renderizadas con Moli para consultarlas tal como se recopilaron.
- [Moli Web Research](https://github.com/assistifyai405/moli-webonderzoek) - Esta herramienta MCP local en fase beta compara capturas guardadas de una página web.
- [molisnap](https://github.com/7a6163/molisnap) - Prerenderiza aplicaciones de una sola página como HTML legible para rastreadores y bots de IA.
- [PageSift](https://github.com/YOLOW92/pagesift) - Recurre a Moli para leer el contenido de los iframes que Lightpanda no detecta.
- [Smart Tool](https://github.com/AllanSantos-DV/smart-tool-dist) - Permite a los agentes de programación en Windows usar Moli cuando una petición HTTP no devuelve el contenido.
- [stvdy](https://github.com/jettapindika/stvdy) - Importa páginas web como material de estudio con Moli cuando Exa no consigue extraer el texto.
- [Vanilla](https://github.com/easylearnfromtw/vanilla) - Permite activar Moli para importar páginas públicas una vez aislado el tráfico saliente.

<a id="agents-and-workspaces"></a>
<a id="agent-frameworks-and-workspaces"></a>

## Frameworks y espacios de trabajo para agentes

- [A3S Code](https://github.com/A3S-Lab/Code) - Configura automáticamente una versión verificada de Moli para las búsquedas web de los agentes de programación.
- [agent-fabric](https://github.com/BlueTeam-OU/agent-fabric) - Proporciona a cada agente de programación su propia sesión temporal de Moli.
- [agnostic-router-kit](https://github.com/adelvillar1/agnostic-router-kit) - Da prioridad a Moli en local cuando un flujo de trabajo necesita leer una página con JavaScript.
- [AION](https://github.com/JayCRL/AION) - Presenta las páginas dinámicas que lee con Moli como tarjetas en el espacio de trabajo del agente.
- [dsh-qq-bot](https://github.com/arrow1031-dev/dsh-qq-bot) - Este bot de QQ puede leer los enlaces compartidos en Markdown con Moli en local.
- [Internkim](https://github.com/yeomyeonggeori/internkim) - Permite al asistente de IA de un equipo navegar por páginas públicas con Moli en local.
- [Lumen](https://github.com/Andrea17982/Lumen) - Incluye una herramienta de navegación con Moli que Claude Code, Codex y otros agentes comparten en el escritorio.
- [mem0-omp](https://github.com/millianlmx/mem0-omp) - Da a los agentes de programación acceso mediante token a un navegador Moli en un contenedor.
- [Qianxun](https://github.com/imxood/qianxun) - Detecta la versión local de Moli en una aplicación de escritorio para DeepSeek Harness.
- [Relay](https://github.com/arcwright42/Relay) - Permite enviar la instrucción aunque Moli agote el tiempo de carga de una página.
- [Wick](https://github.com/yogasw/wick) - Permite a los agentes en Go leer páginas en Markdown con un navegador Moli local opcional.

<a id="deployment-and-packaging"></a>
<a id="packaging-and-deployment"></a>

## Empaquetado y despliegue

Recetas de instalación y plantillas de despliegue de la comunidad.

- [1Panel App](https://github.com/skingko/1panel_app/tree/localApps/apps/x-moli) - Este paquete de la comunidad permite desplegar Moli desde 1Panel.
- [A3S CLI](https://github.com/A3S-Lab/CLI) - Incluye con las herramientas de línea de comandos de A3S la versión de Moli para cada plataforma compatible.
- [Homebrew Moli](https://github.com/hoishing/homebrew-moli) - Este repositorio comunitario de Homebrew instala Moli y las habilidades oficiales para agentes de la misma versión.
- [Lattice](https://github.com/mytecor/lattice/tree/main/profiles/moli) - Aloja Moli en NixOS para depurar páginas a distancia con DevTools.
- [moli-snap](https://github.com/sidalit/moli-snap) - Este paquete Snap no oficial para Linux incluye Moli y fuentes para capturas de pantalla y PDF.
- [orbsh/nixos](https://github.com/orbsh/nixos/blob/main/modules/system/units/moli.nix) - Fija la versión y la suma de verificación de Moli para reproducir la instalación en NixOS.
- [Railway Moli](https://railway.com/deploy/moli?referralCode=sLjDXb) - Despliega Moli en Railway con acceso remoto al navegador protegido por token.

<a id="experimental-and-development-examples"></a>
<a id="development-examples-and-evaluations"></a>

## Ejemplos de desarrollo y evaluaciones

Prototipos, scripts de desarrollo e informes de evaluación. Los resultados de las pruebas proceden de sus autores.

- [Aveli](https://github.com/pkmdev-sec/aveli) - Una prueba experimental verifica que el agente de navegador puede conectarse a Moli en local.
- [govio-map](https://github.com/chenxinma/govio-map) - Escribe con Moli en un campo de configuración para comprobar que conserva el foco al teclear.
- [Hydra Downloader](https://github.com/juanpimg/hydradownloader) - Usa Moli para comprobar si la página de descargas se desborda con distintos anchos de pantalla móvil.
- [laravel-domains](https://github.com/yepbro/laravel-domains) - Compara cómo se comporta su rastreador web con distintas versiones de Moli y con Chromium.
- [llama.rs](https://github.com/yablokolabs/llama.rs) - Comprueba con Moli que su demo local de chat en WebAssembly responde a una pregunta.
- [Master Maps](https://github.com/0bifthenelse/master-maps) - Prueba su mapa 3D de extremo a extremo con Moli y puede recurrir a Chromium en local.
- [Molifasi](https://github.com/A3S-Lab/Molifasi) - Este prototipo de agente usa Apofasi para elegir la siguiente acción que Moli ejecutará en la página.
- [ScopePay AI](https://github.com/yablokolabs/scopepay-ai) - Prueba con Moli la aprobación del pago por parte del comprador en el entorno de pruebas de PayPal.
- [SmartSpecPro](https://github.com/naibarn/SmartSpecPro) - Ejecuta Moli solo en pruebas de aceptación de Linux sin privilegios de root.

## Contribuir

Los forks de Moli, los proyectos derivados y los nuevos usos son bienvenidos. Para proponer un proyecto o mejorar una entrada, consulta la [guía de contribución](../CONTRIBUTING.md).

## Notas

La primera revisión del código y de la documentación públicos se realizó el **2026-11-19**. El uso en producción, las relaciones con clientes y la reproducción independiente de las pruebas quedaron fuera del alcance de la revisión. El [registro de revisión](REVIEW.md) reúne los enlaces a las versiones consultadas, las capturas de las fuentes, las menciones históricas y los repositorios inaccesibles.
