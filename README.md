<a id="top"></a>

<div align="center">
  <img src="assets/banner.svg" alt="Victor Monsalves — ciberseguridad, automatización y desarrollo" width="100%">
</div>

<h1 align="center">Victor Monsalves</h1>

<p align="center">
  <strong>Victor Monsalves</strong><br>
  <sub>Seguridad · Automatización · Herramientas</sub>
</p>

<p align="center">
  <a href="#enfoque">Enfoque</a> ·
  <a href="#ahora">Ahora</a> ·
  <a href="#stack">Stack</a> ·
  <a href="#proyectos">Proyectos</a> ·
  <a href="#principios">Principios</a> ·
  <a href="#contacto">Contacto</a>
</p>

---

## Enfoque

Convierto procesos manuales y repetitivos en flujos que **se ejecutan solos, se pueden
auditar y fallan de forma controlada**. Menos tiempo operativo, menos error humano y
más rastro de lo que pasó.

| Área | Qué hago |
|:--|:--|
| **Automatización de operaciones** | Flujos en n8n que integran APIs, bases de datos y LLM: ingesta, normalización, decisión y publicación con deduplicación persistente. |
| **Tooling de seguridad** | Utilidades para analizar artefactos, revisar configuraciones y detectar credenciales expuestas antes de que lleguen a un repositorio. |
| **IA aplicada** | Modelos con salida estructurada, guardarraíles y revisión humana justo en el punto crítico. |

## Ahora

- Reconstruyendo el portafolio: cada proyecto se publica con README, diagrama de
  arquitectura y guía de despliegue.
- Automatización de ingesta y publicación de noticias con n8n y Groq.
- Endureciendo la cadena de trabajo: hooks anti-secretos, plantillas de proyecto y
  publicación con comprobaciones previas.

## Stack

<p>
  <img alt="n8n" src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
</p>

## Proyectos

Trabajo principalmente en repositorios privados: contienen configuraciones de entornos
reales. El diseño y los flujos se comparten bajo petición.

| Proyecto | Qué resuelve | Stack | Acceso |
|:--|:--|:--|:--|
| **MISP multi-feed ingester** | Ingesta de IOCs multi-feed a MISP | n8n · MISP | Privado |
| **OpenCTI multi-feed intelligence** | Ingesta de threat intelligence multi-feed a OpenCTI | n8n · OpenCTI | Privado |
| **Certificados → RITM** | Crea RITMs en ServiceNow antes de que venza un certificado | n8n · ServiceNow | Privado |
| **Email triage** | Clasificación y triage de correo con LLM | n8n · Groq | Privado |
| **Agente de noticias** | Ingesta de Google News, redacción con LLM y publicación en LinkedIn con deduplicación persistente | n8n · Groq · LinkedIn API | En preparación |

## Principios

- **Guardarraíles primero.** `.env` fuera del repositorio, escaneo de credenciales y
  publicación que aborta si algo no cuadra.
- **Reproducible.** Entornos declarativos, credenciales en el gestor del sistema y
  cero secretos en el código.
- **Documentado.** El README explica el *por qué*, no solo el *qué*; los diagramas se
  entienden sin abrir el editor.
- **Verificado.** Si algo no se puede probar, se dice. El build y los tests son la
  prueba, no la promesa.

## Contacto

La vía más directa es GitHub: abre un *issue* en cualquier repositorio o mencióname
en una discusión. No publico correo para evitar scraping.

---

<div align="center">
  <sub>Perfil mantenido por Victor Monsalves · <a href="#top">Volver arriba</a></sub>
</div>
