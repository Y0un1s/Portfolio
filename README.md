<p align="center">
  <img src="https://avatars.githubusercontent.com/u/134159137?v=4" alt="Younis Profile Picture" width="180" />
</p>

<p align="center">
  <a href="https://github.com/DenverCoder1/readme-typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Time+New+Roman&color=%2305982&size=25&center=true&vCenter=true&width=600&height=100&lines=Data+Engineer;"></a>
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" alt="banner gif" />
</p>

<!-- Hero Title -->
<div id="user-content-toc" align="center">
  <ul>
    <summary><h1 style="display: inline-block">Hello, I'm Ahmed Younis <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35"></h1></summary>
  </ul>
</div>
Enthusiastic Data Engineer with hands-on training in cloud and big-data technologies. Skilled in SQL, Python, PySpark, Microsoft Fabric, and ETL/data ingestion patterns. Experienced building scalable serverless pipelines, infrastructure-as-code, and CI/CD deployments. Looking for my first professional role where I can contribute to data platform development, pipeline automation, and reliable data delivery.

---

## Quick Summary
- Completed intensive training: **6-month Microsoft Data Engineering program** and **4-month Samsung Innovation Campus (Big Data)**.
- Industry certifications: **Microsoft Certified: Fabric Data Engineer Associate**, multiple SQL and Python credentials (Google, DataCamp, HackerRank, 365 Data Science).
- Production-grade project experience: **GG-Analyzer** (serverless AWS pipeline) and **Northwind ETL & Analytics** (data warehouse + automated ETL + Power BI).

---
<!-- Tech Stack Title -->
<div id="user-content-toc" align="center">
  <ul>
    <summary style="margin-bottom: 50px;">
      <h1 style="display: inline-block">Tech Arsenal</h1>
      <picture>
        <img src="https://github.com/7oSkaaa/7oSkaaa/blob/main/Images/about_me.gif?raw=true" width="40px">
      </picture>
    </summary>
  </ul>
</div>

**Languages & Libraries**  
Python · SQL

**Cloud & Platforms**  
AWS · Azure (Microsoft Fabric) · GCP

**Data Ingestion / Messaging**  
SSIS · AWS Glue · Apache Kafka (basic knowledge) · Apache Flume (basic knowledge)

**Data Processing & Preprocessing**  
Apache Spark · Apache Flink (basic knowledge) · Hive · Pandas

**Orchestration**  
Apache Airflow

**Databases & Storage**  
PostgreSQL · MySQL · SQL Server · S3 · Azure Blob · GCS · HDFS

**Data Warehouse & Query Engines**  
Amazon Redshift · Apache Hive · Athena

**BI & Visualization**  
Power BI · Tableau · Excel

**DevOps & Infra**  
Terraform · Docker · Git & GitHub · GitHub Actions · CI/CD

**Other**  
Linux · Agile development workflows

---

## 📜 Selected Certifications
- [Microsoft Certified: Fabric Data Engineer Associate](https://learn.microsoft.com/api/credentials/share/en-us/AhmedYounis-4014/9000AD3C321EDDC6?sharingId=93F850ABF762BF3C) — Microsoft (2025)  
- [Foundations of Data Science](https://www.coursera.org/account/accomplishments/records/3VCDTTNFCYYJ) — Google (2025)  
- [SQL Associate](https://www.datacamp.com/certificate/SQA0017092171929) — DataCamp (2025)  
- [SQL (Intermediate)](https://www.hackerrank.com/certificates/4a89ac7444bb) — HackerRank (2025)  
- [Get Started with Python](https://coursera.org/share/71ea989bdc673ebd4458e4503e8e8098) — Google (2025)  
- [Advanced SQL for Data Engineering](https://learn.365datascience.com/c/cf65be37e7) — 365 Data Science (2024)  
- [The Legend of Python](https://www.credential.net/81dbc84a-e998-42f8-b09a-1fd2849f27fb#acc.0YVvBUKD) — 365 Data Science  
- [Certificate of completion - Advanced SQL](https://learn.365datascience.com/c/fa09763044) — 365 Data Science  
- [Certificate of completion - SQL](https://learn.365datascience.com/c/bd596b83c8) — 365 Data Science

---

## 📂 Projects

### [GG-Analyzer — Serverless Data Engineering Pipeline for League of Legends](https://github.com/Y0un1s/gganalyzer-iac)  
<div align="center">
  <a href="https://github.com/Y0un1s/gganalyzer-iac">
    <img src="https://github.com/Y0un1s/gganalyzer-iac/blob/main/assets/architecture_diagram.png?raw=true" alt="GG-Analyzer PIC" width="250">
  </a>
</div>

**Tech stack:** AWS Lambda, Amazon S3, Amazon SQS (FIFO), DynamoDB, AWS Glue, Athena, Terraform, GitHub Actions, Secrets Manager, Power BI, Python

**Overview:**  
Production-grade serverless pipeline that ingests match data from the Riot Games API, performs resilient ETL, catalogs data in Glue, and serves metrics to Power BI via Athena.

**Key contributions:**
- Architected a decoupled serverless pipeline (SQS FIFO + Lambda).
- Implemented batching & re-queueing to avoid Lambda timeouts.
- Ensured idempotency and state with DynamoDB.
- Built rate-limit handling (exponential backoff, SQS delays).
- Automated infra with Terraform and CI/CD via GitHub Actions.
- Created semantic views and role-weighted metrics for analytics.

**Impact:** Fault-tolerant ingestion pipeline enabling analysts to query precomputed metrics and reducing ETL overhead.

---

### [Northwind ETL & Analytics — Data Warehouse](https://github.com/Y0un1s/Northwind-Data-Solution)
<div align="center">
  <a href="https://github.com/Y0un1s/Northwind-Data-Solution">
    <img src="https://user-images.githubusercontent.com/74038190/221352987-68da234d-4d62-4e9d-9d7f-098dc657c2dc.gif" alt="Northwind Data Solution GIF" width="150">
  </a>
</div>

**Tech stack:** SQL Server (OLTP & DW), SSIS, SSMS, Snowflake schema, Power BI, SQL Agent

**Overview:**  
Maintainable data warehouse for the Northwind dataset: modeling (conceptual → logical → physical), automated ETL (SSIS), and Power BI dashboards.

**Key contributions:**
- Designed a snowflake schema with normalized dimensions and a Fact_Orders table.
- Built SSIS packages for ODS → Staging → DW pipeline and automated refresh via SQL Agent.
- Optimized storage and removed unnecessary binary columns.
- Delivered dashboards for Sales, Inventory, Customer Segmentation, and Employee Performance.
- Documented ETL workflows and test cases.

**Outcome:** Documented data solution converting raw OLTP data into business-ready analytics assets.



## 💡 How I work
- I design for reliability: resilient pipelines, idempotent processing, and automated recovery.  
- I automate: IaC (Terraform), CI/CD (GitHub Actions), secret management, and scheduled refreshes.  
- I focus on clean, queryable data for analysts: semantic views, precomputed KPIs, and simple access patterns (Athena / SQL / Power BI).

---
<!-- Connect with me -->
<div id="user-content-toc" align="center">
  <ul>
    <summary><h1 style="display: inline-block">Let's Connect</h1><img src="https://user-images.githubusercontent.com/74038190/216120981-b9507c36-0e04-4469-8e27-c99271b45ba5.png" width="30"></summary>
  </ul>
</div>
<p align="center">
  <a href="https://www.linkedin.com/in/ahmed-younis-o" target="_blank"><img src="https://user-images.githubusercontent.com/74038190/235294012-0a55e343-37ad-4b0f-924f-c8431d9d2483.gif" alt="linkedin" height="48" width="48" /></a>
  <a href="https://github.com/Y0un1s" target="_blank"><img src="https://simpleicons.org/icons/github.svg" alt="github" height="40" width="40" style="filter: invert(1);" /></a>
  <a href="mailto:ahmedyounisokal@gmail.com" target="_blank"><img src="https://simpleicons.org/icons/gmail.svg" alt="email" height="40" width="40" /></a>
</p>

---

