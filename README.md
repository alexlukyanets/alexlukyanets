<a href="https://oleksandr.62-238-84-212.sslip.io/">
  <img src="./assets/header.svg" width="100%" alt="Oleksandr Lukianets - AI engineer and web developer in Valencia, Spain">
</a>

<p align="center">
  <img src="./assets/typing.svg" width="100%" alt="I put language models to work for real businesses">
</p>

<p align="center">
  <a href="https://oleksandr.62-238-84-212.sslip.io/"><img alt="Website" src="https://img.shields.io/badge/Website-0b0e14?style=for-the-badge&logo=googlechrome&logoColor=e7a25c"></a>
  <a href="https://wa.me/34600595224"><img alt="WhatsApp" src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"></a>
  <a href="https://t.me/lukyanetsalex"><img alt="Telegram" src="https://img.shields.io/badge/Telegram-2AABEE?style=for-the-badge&logo=telegram&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/alexandr-lukyanets/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
</p>

## Hi, I'm Oleksandr

**AI engineer and web developer in Valencia, Spain.** I put language models to work - LLM data extraction, RAG search, AI agents with MCP, voice assistants - and wrap them in fast, beautiful websites and Telegram bots your clients actually use. 5+ years of commercial Python, platforms with 1.5M+ records.

<sub>🇪🇸 Ingeniero de IA y desarrollador web en Valencia: páginas web, asistentes de IA, bots de Telegram y backends en Python. · 🇺🇦 AI-інженер і веб-розробник у Валенсії.</sub>

- 🛰️ **Now:** backend engineer in the core team of an OSINT platform - async collection, reliability, MCP tools for AI agents
- 🧠 **Building:** [Holy](https://oleksandr.62-238-84-212.sslip.io/#projects), my own AI assistant that runs my day on my own server
- 🌐 **For clients:** landing pages and business sites, AI assistants and chatbots, scrapers and data pipelines, Python APIs
- 📍 **Where:** Valencia, Spain · CET · remote for EU, UK, US or in person in Valencia
- 💬 **Ask me about:** RAG, LLM extraction, MCP agents, FastAPI, web scraping at scale, Telegram bots

## Selected work

<sub>Client code stays private. These are real systems, the problems and how I solved them. Full cases on <a href="https://oleksandr.62-238-84-212.sslip.io/#projects">the site</a>.</sub>

<table>
  <tr>
    <td width="50%"><a href="https://oleksandr.62-238-84-212.sslip.io/#projects"><img src="./assets/project-holy.svg" width="100%" alt="Holy: my personal AI operating system"></a></td>
    <td width="50%"><a href="https://oleksandr.62-238-84-212.sslip.io/#projects"><img src="./assets/project-realestate.svg" width="100%" alt="US real-estate data platform, 1.5M+ records via API"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://oleksandr.62-238-84-212.sslip.io/#projects"><img src="./assets/project-slapi.svg" width="100%" alt="SL API: OSINT intelligence platform with MCP tools"></a></td>
    <td width="50%"><a href="https://oleksandr.62-238-84-212.sslip.io/#projects"><img src="./assets/project-property.svg" width="100%" alt="Valencia property check: listing to cadastre to land registry"></a></td>
  </tr>
</table>

<details>
<summary><b>🧠 How Holy works - click to open the architecture</b></summary>
<br>

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#0b0e14','primaryTextColor':'#f1ede6','primaryBorderColor':'#8fb4d8','lineColor':'#e7a25c','secondaryColor':'#11151d','tertiaryColor':'#0b0e14','fontFamily':'monospace'}}}%%
flowchart LR
  TG["📱 Telegram / Web"] --> BOT["Capture bot"]
  BOT -->|voice| W["🎙️ Local Whisper large-v3"]
  W --> R{"🧠 LLM router"}
  BOT -->|text, photo| R
  R -->|receipt| L["🧾 Ledger"]
  R -->|remind me| CAL["📅 Calendar"]
  R -->|meal, scale| N["📒 Notion via FastAPI"]
  R -->|open the site| B["🌐 Browser over CDP"]
  N --> M["☀️ Morning brief 06:00"]
```

</details>

<details>
<summary><b>🏢 Experience - five years of production code</b></summary>
<br>

| When | Where | What |
|---|---|---|
| 2026 - now | **Social Links** · Backend engineer, core team | OSINT platform: API integrations, async collection, production reliability, MCP tooling for AI agents |
| 2024 - 2026 | **Niche Solutions** · Senior Python developer, parsing team lead | US real-estate data platform with API access to 1.5M+ records; LLM extraction with OpenAI and Llama, RAG with ChromaDB |
| 2022 - 2023 | **Codifire** · Python developer | AI content engine for SEO on Django REST and OpenAI; Telegram assistant for a medical clinic |
| 2021 - 2022 | **Bldup** · Python developer | Collectors for construction permits, mortgages, leases and deeds with Scrapy and PDF processing |

</details>

## Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,django,flask,postgres,mongodb,redis,docker,kubernetes,githubactions,linux,git&perline=12&theme=dark" alt="Python, FastAPI, Django, Flask, PostgreSQL, MongoDB, Redis, Docker, Kubernetes, GitHub Actions, Linux, Git"><br><br>
  <img src="https://skillicons.dev/icons?i=js,ts,html,css,tailwind,nodejs,astro,gcp,aws,nginx,selenium,bash&perline=12&theme=dark" alt="JavaScript, TypeScript, HTML, CSS, Tailwind, Node.js, Astro, GCP, AWS, Nginx, Selenium, Bash">
</p>

<p align="center"><sub><b>AI:</b> OpenAI · Claude · Llama · LangChain · RAG · ChromaDB · MCP · Whisper &nbsp;·&nbsp; <b>Data:</b> Scrapy · Playwright · CDP · gRPC · Celery · PostGIS</sub></p>

## Need a site or an AI assistant?

Write one message with your idea - I usually reply the same day.

<a href="https://oleksandr.62-238-84-212.sslip.io/">
  <img src="./assets/footer.svg" width="100%" alt="Let's build something that shines - WhatsApp, Telegram, LinkedIn">
</a>

<p align="center"><sub>Oleksandr Lukianets · AI engineer & web developer · Valencia, Spain · <a href="https://oleksandr.62-238-84-212.sslip.io/">oleksandr.62-238-84-212.sslip.io</a></sub></p>
