<h1 align="center">👋 Hi, I'm Evgeniy</h1>

<p align="center">
  <b>Data Engineer · ITMO University · Python / SQL / DWH</b>
</p>

<p align="center">
  Building data pipelines, warehouses and analytics systems.
</p>

<p align="center">
  <a href="mailto:zma54211@gmail.com">📧 Email</a>
  ·
  <a href="https://github.com/1nf6ct6d">🐙 GitHub</a>
</p>

---

```text
evgeniy@itmo:~/data-engineering$ whoami

ROLE        → Data Engineer
FOCUS       → ETL / ELT · DWH · Data Pipelines · Analytics
STACK       → Python · SQL · Airflow · ClickHouse · PostgreSQL
EDUCATION   → ITMO University · Cybersecurity
STATUS      → OPEN TO INTERNSHIP
```

> [!IMPORTANT]
> 🟢 **Open to Data Engineering internship opportunities / Открыт к предложениям на стажировку Data Engineer**

---

## 👨‍💻 About Me / Обо мне

| 🇬🇧 English | 🇷🇺 Русский |
|---|---|
| 🎯 Looking for a **Data Engineering internship** | 🎯 Ищу стажировку в направлении **Data Engineering** |
| 🎓 **ITMO University** — Faculty of Cybersecurity | 🎓 **ИТМО** — факультет кибербезопасности |
| 🌍 Russia | 🌍 Россия |
| 🔥 **Winner & Finalist — Russian IT CUP 2026** | 🔥 **Победитель и финалист первого тура Russian IT CUP 2026** |

---

## 🛠 Tech Stack

### Data Engineering

<kbd>Python</kbd>
<kbd>SQL</kbd>
<kbd>ETL / ELT</kbd>
<kbd>Apache Airflow</kbd>
<kbd>ClickHouse</kbd>
<kbd>Oracle DWH</kbd>
<kbd>PostgreSQL</kbd>
<kbd>MinIO</kbd>

### Backend & Infrastructure

<kbd>FastAPI</kbd>
<kbd>Docker</kbd>
<kbd>Linux</kbd>
<kbd>Bash</kbd>
<kbd>Git</kbd>
<kbd>GitHub Actions</kbd>
<kbd>REST API</kbd>

### Data Processing

<kbd>Pandas</kbd>
<kbd>JSON</kbd>
<kbd>CSV</kbd>
<kbd>API Ingestion</kbd>
<kbd>Data Modeling</kbd>
<kbd>Analytics</kbd>

---

## ⚙️ Data Engineering Workflow

```mermaid
flowchart LR
    API["🌐 APIs"] --> ING["📥 Ingestion"]
    ING --> RAW["🗄 Raw / Staging"]
    RAW --> ETL["⚙️ ETL / ELT"]
    ETL --> DWH["🏛 DWH"]
    DWH --> SERVE["⚡ Serving Layer"]
    SERVE --> BI["📊 Analytics"]

    AIRFLOW["🌪 Airflow"] -. orchestration .-> ING
    AIRFLOW -. orchestration .-> ETL
    AIRFLOW -. orchestration .-> SERVE
```

<p align="center">
  <b>Ingest → Store → Transform → Model → Serve → Analyze</b>
</p>

---

# 🚀 Featured Projects

## 🟡 F1 DATA WAREHOUSE ANALYTICS SYSTEM

**End-to-End Data Engineering / DWH**

<kbd>Python</kbd>
<kbd>ETL</kbd>
<kbd>Oracle DWH</kbd>
<kbd>ClickHouse</kbd>
<kbd>Airflow</kbd>
<kbd>MinIO</kbd>
<kbd>FastAPI</kbd>

🔗 **Repository:**  
https://github.com/1nf6ct6d/F1-Data-Warehouse-Analytics-System

**RU:** End-to-end Data Engineering проект: API ingestion → raw/staging в MinIO → dimensions и facts в Oracle DWH → analytics views → serving-слой в ClickHouse → оркестрация через Airflow → FastAPI.

**Pipeline:**

```text
Public API
    │
    ▼
 Raw Data
    │
    ▼
   MinIO
raw / staging
    │
    ▼
Oracle DWH
dimensions + facts
    │
    ▼
Analytics Views
    │
    ▼
ClickHouse
serving layer
    │
    ▼
FastAPI
```

---

## 🟡 CUPIT 2026 — AI SEARCH ANALYSIS FOR FMCG BRANDS

**Data Engineering / API Ingestion / Analytics**

<kbd>Python</kbd>
<kbd>ETL</kbd>
<kbd>API</kbd>
<kbd>PostgreSQL</kbd>
<kbd>SQL</kbd>
<kbd>Pandas</kbd>

🔗 **Repository:**  
https://github.com/1nf6ct6d/CupIT2026-Data-Engineering-AI-Search-Analysis-for-FMCG-Brands

**RU:** Data pipeline для анализа AI Search: сбор данных через API → обработка и нормализация ответов → извлечение источников и упоминаний брендов → PostgreSQL → SQL-анализ.

```text
Search API
    ↓
Data Collection
    ↓
Normalization
    ↓
Brand / Source Extraction
    ↓
PostgreSQL
    ↓
SQL Analytics
```

---

## 🟡 ALPHACUP 2026

**Multi-Source Data Pipeline / NLP**

<kbd>Python</kbd>
<kbd>ETL</kbd>
<kbd>YouTube</kbd>
<kbd>VK</kbd>
<kbd>Telegram</kbd>
<kbd>NLP</kbd>

🔗 **Repository:**  
https://github.com/1nf6ct6d/AlphaCup2026

**RU:** Multi-source data pipeline для сбора пользовательских комментариев из YouTube, VK и Telegram: ingestion → унификация данных → дедупликация → обработка текста → анализ пользовательских проблем.

```text
YouTube ─┐
VK      ─┼─→ Ingestion → Normalize → Deduplicate → NLP → Analytics
Telegram ─┘
```

---

## 🟡 OZONTECH ROBOZON SORTING SYSTEM

**Engineering / Computer Vision / Data Pipeline**

<kbd>Python</kbd>
<kbd>FastAPI</kbd>
<kbd>YOLO</kbd>
<kbd>Blender</kbd>
<kbd>PyBullet</kbd>
<kbd>Docker</kbd>

🔗 **Repository:**  
https://github.com/1nf6ct6d/OzonTech-Robozon-sorting-system

**RU:** Инженерная система автоматической сортировки товаров: обработка изображений → CV pipeline на YOLO → генерация synthetic datasets в Blender → FastAPI backend → симуляция сортировочной линии.

```text
Product Data
     ↓
Synthetic Dataset
   (Blender)
     ↓
    YOLO
     ↓
Classification
     ↓
   FastAPI
     ↓
Sorting Simulation
   (PyBullet)
```

---

# 📂 More Projects

<details>
<summary><b>🟡 CENTRALIZED DRIVING SCHOOL DATABASE</b></summary>

<br>

<kbd>Python</kbd>
<kbd>SQL</kbd>
<kbd>Database</kbd>
<kbd>Backend</kbd>

🔗 https://github.com/1nf6ct6d/CENTRALIZED_DRIVING_SCHOOL_DATABASE

**RU:** Централизованная система хранения и обработки данных автошкол с использованием Python и SQL.

</details>

---

<details>
<summary><b>🟡 API-TO-CSV-CONVERTER</b></summary>

<br>

<kbd>Python</kbd>
<kbd>API Ingestion</kbd>
<kbd>JSON</kbd>
<kbd>ETL</kbd>
<kbd>CSV</kbd>

🔗 https://github.com/1nf6ct6d/API-TO-CSV-CONVERTER

**RU:** Простой ETL pipeline: получает данные из публичного API → сохраняет raw JSON → преобразует данные → экспортирует структурированный CSV.

</details>

---

<details>
<summary><b>🟡 YAHOO FINANCE EXTRACTOR</b></summary>

<br>

<kbd>Python</kbd>
<kbd>API</kbd>
<kbd>Data Extraction</kbd>
<kbd>Automation</kbd>

🔗 https://github.com/1nf6ct6d/YAHOO-FINANCE-TRACKER

**RU:** Автоматизированный pipeline для извлечения и обработки финансовых данных из Yahoo Finance.

</details>

---

## 🏆 Highlights

```text
┌──────────────────────────────────────────────────────────────┐
│  Russian IT CUP 2026                                        │
│                                                              │
│  🏆 Winner                                                   │
│  🔥 Finalist                                                 │
│  🎓 ITMO University                                         │
│  ⚙️ Data Engineering                                        │
└──────────────────────────────────────────────────────────────┘
```

---

## 🎯 Current Focus

```yaml
learning:
  - Advanced SQL
  - Data Warehousing
  - ETL / ELT Architecture
  - Apache Airflow
  - ClickHouse
  - Data Modeling

building:
  - Data Pipelines
  - DWH Systems
  - API Ingestion
  - Analytics Platforms

target:
  role: Data Engineer Intern
  status: open_to_opportunities
```

---

## 📫 Contacts

**Email:** [zma54211@gmail.com](mailto:zma54211@gmail.com)  
**GitHub:** [github.com/1nf6ct6d](https://github.com/1nf6ct6d)

---

<p align="center">
  <b>Data is only useful when you can move it, model it and trust it.</b>
</p>

<p align="center">
  <code>ingest() → transform() → model() → serve()</code>
</p>
