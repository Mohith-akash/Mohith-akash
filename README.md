# Mohith Akash

**Data Engineer**

[LinkedIn](https://www.linkedin.com/in/mohith-akash/) · [Email](mailto:mohithakash013@gmail.com) · Germany

I build data pipelines, warehouses and LLM features. 3 live projects, 30M+ records processed, 9,000+ users.

## About me

I ran MAS Nexus, my own data consultancy, for over two years, doing data work for client companies: pipelines, warehouse models, 15+ dashboards and reports, and later AI features. The longest engagement ran 27 months as an embedded data engineer. The platforms below were built alongside. Reference letter available on request.

Based in Berlin with a Chancenkarte (Opportunity Card). I can start right away part-time and move to full-time through a Blue Card or skilled worker permit; the employer signs one form and pays no fees.

## Projects

### [Global News Intelligence Platform](https://github.com/Mohith-akash/Global-News-Intel-Platform) · [live demo](https://global-news-intel-platform.streamlit.app/)

Data pipeline over 30M+ geopolitical news events from GDELT, live since December 2025.

- 9,000+ unique visitors since launch, zero advertising
- About 100K events ingested a day on an hourly schedule, dbt marts with 30+ tests built weekly
- Two-mode AI chat: RAG over vector embeddings, plus SQL answers from tested query templates
- Slowest stage rewritten from Pandas to Polars: 91 seconds down to 6
- $0/month: MotherDuck + Dagster + GitHub Actions on free tiers

`Python` `Polars` `dbt` `MotherDuck` `Dagster` `Great Expectations`

### [Vortex: Revenue Recovery Engine](https://github.com/Mohith-akash/Vortex-The-Revenue-Recovery-Engine) · [live demo](https://vortex-the-revenue-recovery-engine.streamlit.app/)

Streaming platform for AI-powered cart-abandonment recovery, run on simulated storefront traffic.

- Azure Event Hubs streaming into Delta Live Tables (Bronze, Silver, Gold)
- LLM-personalized recovery messages across 5 customer archetypes
- Medallion lakehouse (Bronze/Silver/Gold) with DLT expectations
- A/B testing with z-scores at 95% confidence (simulated sessions)

`Databricks` `Azure Event Hubs` `DLT` `Cerebras` `dbt` `Streamlit`

### [Olist E-Commerce Analytics](https://github.com/Mohith-akash/olist-analytics-platform) · [live demo](https://olist-analytics-platform.streamlit.app/)

Databricks lakehouse over ~99K orders from the Brazilian Olist marketplace.

- Medallion architecture with Delta Lake
- Kimball star schema: fct_orders + customer/product/seller dimensions
- Bronze, Silver and Gold in separate Unity Catalog schemas; the dashboard reads Gold only

`Databricks` `Delta Lake` `SQL` `Unity Catalog` `Power BI`

### [German Frequency Deck](https://github.com/Mohith-akash/german-frequency-deck)

Anki deck with 5,000+ German words across A1 to C1, built while learning German myself. 9,000+ downloads on AnkiWeb, all organic.

- Designed the build pipeline with AI: word selection by frequency and learner need
- Neural audio for every word, images, verb conjugations

`Python` `Anki` `Text-to-Speech`

### [Job Market Analysis Dashboard](https://github.com/Mohith-akash/Excel-Data-Analyst-Portfolio-Project)

Interactive Excel dashboard analyzing 12,894 data job postings.

- 70+ step Power Query ETL, 228K+ rows in Power Pivot with custom DAX
- 6,797 messy job titles standardized into about 20 roles

`Excel` `Power Query` `Power Pivot` `DAX`

## Tools

- **Data engineering:** Python · SQL · Databricks · Delta Lake · Azure · DuckDB/MotherDuck
- **Pipelines:** dbt Core · Dagster · Polars · Great Expectations · GitHub Actions
- **AI/LLM:** RAG · LlamaIndex · Cerebras · Voyage AI embeddings
- **Visualization:** Streamlit · Plotly · Power BI

---

**Data Engineer. Open to Data Engineer, Analytics Engineer, AI Engineer and Data Analyst roles in Germany.** Chancenkarte holder in Berlin, English C1, German A2 (working toward B1).

B.Tech, Electrical and Electronics Engineering, SRM Institute of Science and Technology, Chennai
