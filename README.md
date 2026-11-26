<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a8a,100:0284c7&height=185&section=header&text=Gian%20Martinez&fontSize=42&fontColor=ffffff&fontAlignY=36&desc=Software%20Developer%20%E2%80%A2%20Data%20Engineer%20%E2%80%A2%20Data%20Analyst&descAlignY=62&descSize=16" alt="Gian Martinez Header"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/gianmartinezvilla/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:gianfrancovillam@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/gmartine32/elt-datos-publicos">
    <img src="https://img.shields.io/badge/Featured%20Project-SECOP%20II%20ELT-0284c7?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Proyecto Destacado"/>
  </a>
</p>

---

### Hola, soy Gian Martinez
Combino **Ingeniería de Software**, **Ingeniería de Datos en la Nube (GCP)** y **Analítica de Datos** para construir soluciones de punta a punta: desde la arquitectura del código y pipelines automatizados hasta tableros ejecutivos que convierten datos crudos en decisiones de negocio.

---

### Mis 3 pilares técnicos

#### 1. Ingeniería de Software & Desarrollo
- Diseño de código modular, tipado y mantenible en **Python** (CLIs con `argparse`, configuración por entorno, logging estructurado y consumo resiliente de APIs REST con reintentos exponenciales).
- Contenerización reproducible con **Docker**, automatización **CI/CD** con **GitHub Actions** y control de versiones profesional con **Git**.
- Buenas prácticas de seguridad (principio de mínimo privilegio IAM, gestión segura de secretos y pruebas automatizadas).

#### 2. Ingeniería de Datos (Data Engineering)
- Pipelines **ELT modernos** con **Arquitectura Medallion (Bronze, Silver, Gold)** en **Google Cloud Platform (GCS + BigQuery)**.
- Ingesta incremental e idempotente en formato **Parquet** particionado estilo Hive, manejo de *schema drift*, particionamiento y *clustering* en Data Warehouses.
- Transformaciones versionadas, documentación y calidad de datos con **dbt Core** (*data tests* y *unit tests*).

#### 3. Analítica de Datos & BI (Data Analytics)
- Limpieza, perfilado y modelado dimensional (tablas de hechos y dimensiones) orientado a negocio.
- Consultas analíticas avanzadas en **SQL** (funciones ventana, agregaciones y optimización de consultas) y análisis exploratorio con **Pandas / PyArrow**.
- Diseño de KPIs, seguimiento operativo y dashboards interactivos en **Looker Studio**.

---

### Stack Tecnológico

| Área | Tecnologías |
| :--- | :--- |
| **Software & DevOps** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| **Data Engineering & Cloud** | ![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white) ![GCS](https://img.shields.io/badge/Cloud%20Storage-4285F4?style=flat-square&logo=googlecloudstorage&logoColor=white) ![dbt](https://img.shields.io/badge/dbt%20Core-FF694B?style=flat-square&logo=dbt&logoColor=white) ![Parquet](https://img.shields.io/badge/PyArrow%20%2F%20Parquet-013243?style=flat-square&logo=apache&logoColor=white) |
| **Data Analytics & BI** | ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![Looker Studio](https://img.shields.io/badge/Looker%20Studio-4285F4?style=flat-square&logo=looker&logoColor=white) |

---

### Proyecto Destacado

#### [ELT Datos Públicos — SECOP II (Medallion Architecture en GCP)](https://github.com/gmartine32/elt-datos-publicos)
Pipeline ELT diario de producción que ingesta contratos públicos reales de Colombia (`datos.gov.co`) y entrega capas analíticas validadas listas para BI:
- **Software & Orquestación:** CLI en Python con paginación determinística (`$order=:id`), filtros geográficos y backfilling, contenedor **Docker** y ejecución diaria automatizada en **GitHub Actions**.
- **Data Engineering:** Data Lake **Bronze** en **GCS (Parquet)** + carga idempotente a **BigQuery** vía *partition decorators* (`$YYYYMMDD` + `WRITE_TRUNCATE`) con 0 duplicados.
- **Data Analytics & Calidad:** Capas **Silver** y **Gold** en **dbt Core** (tablas particionadas/clusterizadas + **29 data tests y 3 unit tests**) conectadas a **Looker Studio** para análisis por departamento, municipio, entidad y proveedor PyME.

---

### Estadísticas de GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=gmartine32&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gmartine32&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages"/>
</p>
