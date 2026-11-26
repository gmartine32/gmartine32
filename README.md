<p align="center">
  <img src="./assets/header.svg" width="100%" alt="Gian Franco Martinez — Senior Full Stack, AI & Data Engineer"/>
</p>

<p align="center">
  <a href="https://gianmartinez.space">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&duration=3200&pause=1100&color=38BDF8&center=true&vCenter=true&width=780&height=36&lines=Senior+Full+Stack+Engineer+%E2%80%A2+TypeScript+%E2%80%A2+React+%E2%80%A2+Node.js+%E2%80%A2+FastAPI;AI+%26+RAG+Systems+Builder+%E2%80%A2+OpenAI+%E2%80%A2+Anthropic+%E2%80%A2+Tool+Calling;Data+Engineer+%26+Analyst+%E2%80%A2+GCP+%E2%80%A2+BigQuery+%E2%80%A2+dbt+Core+%E2%80%A2+Kafka+%E2%80%A2+PostgreSQL" alt="Typing SVG"/>
  </a>
</p>

<p align="center">
  <a href="https://gianmartinez.space">
    <img src="https://img.shields.io/badge/Portfolio-gianmartinez.space-0F172A?style=for-the-badge&logo=vercel&logoColor=38BDF8" alt="Portfolio"/>
  </a>
  <a href="https://www.linkedin.com/in/gianmartinezvilla/">
    <img src="https://img.shields.io/badge/LinkedIn-gianmartinezvilla-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:gianfrancovillam@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contacto-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

### Sobre mí
**Ingeniero de Sistemas** *(Mención de Honor, Universidad de la Costa CUC)* con **+4 años de experiencia** construyendo plataformas transaccionales de alta concurrencia, **agentes inteligentes (RAG + Tool Calling)** y **pipelines de datos modernos en la nube (GCP)**.

Opero en la intersección de **Ingeniería de Software, IA Aplicada y Datos**: llevo soluciones desde la arquitectura backend y bases de datos hasta pipelines ELT automatizados y tableros analíticos que impactan directamente el negocio.

<div align="center">

| +750 Estaciones | -40% Carga | -50% Deploys | 2.5x Velocidad IA |
| :---: | :---: | :---: | :---: |
| Plataforma transaccional nacional (**Terpel**) | Optimización Full Stack & SQL | CI/CD con **Docker + GitHub Actions** | Flujo **Claude Code / Cursor + Spec-Driven** |

</div>

---

### Mis 3 Pilares de Ingeniería

| Ingeniería de Software & Full Stack | Agentes IA & Sistemas RAG | Data Engineering & Analytics |
| :--- | :--- | :--- |
| Plataformas transaccionales y microservicios en **TypeScript, React, Next.js, Node.js, FastAPI, Go y Spring Boot**. | Integración de **OpenAI, Anthropic y Gemini** con flujos agénticos, **Tool Calling** y salidas estructuradas (*JSON Schema*). | Pipelines **ELT** con **Arquitectura Medallion (Bronze, Silver, Gold)** en **GCP (GCS + BigQuery)** y **Parquet**. |
| Arquitecturas orientadas a eventos (**Kafka, WebSockets, Webhooks**), **PostgreSQL / PL-SQL** y observabilidad con **Sentry**. | Pipelines **RAG** completos: chunking semántico, **vector embeddings** y recuperación contextual de alta precisión. | Transformaciones y calidad con **dbt Core** (*data & unit tests*), **SQL analítico**, **Pandas** y **Looker Studio**. |

---

### Experiencia & Proyectos Destacados

#### Ingeniería de Datos & Analítica
- **[ELT Datos Públicos — SECOP II (Medallion Architecture en GCP)](https://github.com/gmartine32/elt-datos-publicos)**
  Pipeline ELT diario en producción con datos reales de contratación estatal (`datos.gov.co`). Extracción incremental en **Python** con paginación determinística (`$order=:id`) y Parquet particionado Hive -> **GCS** -> **BigQuery** idempotente vía *partition decorators* (`$YYYYMMDD` + `WRITE_TRUNCATE`, 0 duplicados) -> **dbt Core** (capas Silver & Gold particionadas/clusterizadas + **32 pruebas automatizadas**) -> **Docker + GitHub Actions** -> **Looker Studio**.

#### Inteligencia Artificial & Productos Propios
- **Papyria — Founder & AI / Full Stack Engineer** *(2024 – 2025)*
  Lector documental multiplataforma impulsado por agentes conversacionales (**OpenAI / Anthropic**). Pipeline **RAG** end-to-end (segmentación semántica, *vector embeddings*, salidas estructuradas), backend en **Python (FastAPI)** + **Node.js** + **PostgreSQL**, *tool calling* y *webhooks* para sincronización en la nube.

#### Ingeniería de Software a Escala (Producción)
- **Devitech S.A.S – Terpel — Senior Full Stack & AI-Accelerated Engineer** *(2021 – Actualidad)*
  Evolución full stack de plataforma transaccional que soporta **+750 estaciones de servicio Terpel** a nivel nacional (**-40% tiempos de carga**, **-50% ciclos de despliegue**). **TypeScript, React, Node.js, PostgreSQL/PL-SQL, Kafka, WebSockets, Docker, GitHub Actions y Sentry**.
- **Populi S.A. / MoviSAI / Consultoría Full Stack** *(2022 – 2025)*
  - **Premios Perrenque:** plataforma completa de postulación y votaciones en **Next.js / React + PostgreSQL**.
  - **ODR Logística:** sistema de ruteo y trazabilidad en **React + Node.js** con **Google Maps / Routes APIs** y webhooks.
  - **MoviSAI (Gob. de San Andrés):** plataforma web/móvil de censo vehicular (**-40% tiempo de registro operativo**).
  - **Beefree & Begima:** microservicio de reportería/analítica en **Node.js** (**-50% tiempo de procesamiento**) y e-commerce en **React** (**+18% conversiones**).

---

### Stack Tecnológico

| Dominio | Herramientas |
| :--- | :--- |
| **Frontend** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React Native](https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |
| **Backend & Messaging** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) |
| **AI & LLM Engineering** | ![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white) ![Anthropic](https://img.shields.io/badge/Anthropic%20Claude-191919?style=flat-square&logo=anthropic&logoColor=white) ![Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white) ![RAG](https://img.shields.io/badge/RAG%20%26%20Embeddings-6366F1?style=flat-square&logo=langchain&logoColor=white) |
| **Data Engineering & BI** | ![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white) ![GCS](https://img.shields.io/badge/Cloud%20Storage-4285F4?style=flat-square&logo=googlecloudstorage&logoColor=white) ![dbt Core](https://img.shields.io/badge/dbt%20Core-FF694B?style=flat-square&logo=dbt&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20%2F%20PL--SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas%20%2F%20PyArrow-150458?style=flat-square&logo=pandas&logoColor=white) ![Looker Studio](https://img.shields.io/badge/Looker%20Studio-4285F4?style=flat-square&logo=looker&logoColor=white) |
| **Cloud, DevOps & Observability** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white) ![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) |

---

### Actividad en GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=gmartine32&show_icons=true&theme=tokyonight&bg_color=0D1117&border_color=1E293B&title_color=38BDF8&icon_color=818CF8" alt="GitHub Stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gmartine32&layout=compact&theme=tokyonight&bg_color=0D1117&border_color=1E293B&title_color=38BDF8" alt="Top Languages"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=gmartine32&bg_color=0D1117&color=94A3B8&line=38BDF8&point=818CF8&area=true&area_color=1E3A8A&hide_border=false&custom_title=Contribution%20Activity" width="100%" alt="GitHub Activity Graph"/>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:070B14,50:1e3a8a,100:0284c7&height=90&section=footer" width="100%" alt="Footer"/>
</p>
