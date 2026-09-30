<!-- Inspired by portfoliodevraj.vercel.app: black stage, cream type, periwinkle accent, handwritten notes. No asset folder needed. -->

<a href="https://portfoliodevraj.vercel.app/">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=000000&height=190&text=DEVRAJ%20BIJPURIA&fontColor=FFFCF3&fontSize=64&fontAlignY=46&desc=data%20engineering%20%E2%80%A2%20ML&descColor=A8AEF5&descSize=16&descAlignY=74&animation=fadeIn" width="100%" alt="Devraj Bijpuria">
</a>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Geist+Mono&size=16&duration=2600&pause=900&color=A8AEF5&background=00000000&center=true&vCenter=true&width=640&lines=%3E+whoami;final-year+B.Tech+CSE+%40+VIT+Bhopal+(2027);I+build+pipelines+that+run+themselves;S3+%E2%86%92+Snowflake+%E2%86%92+dbt+%E2%86%92+Airflow" alt="typing intro">
</p>

<p align="center">
  <a href="#about"><code>about</code></a>&nbsp;&nbsp;
  <a href="#skill-sets"><code>skill sets</code></a>&nbsp;&nbsp;
  <a href="#projects"><code>projectssss</code></a>&nbsp;&nbsp;
  <a href="#contact"><code>contact</code></a>
</p>

<br>

## about

```text
sys/about ─────────────────────────────────────────────────────────────
  Devraj Bijpuria · Computer Science @ VIT Bhopal · class of 2027

  I got into data engineering after wondering what actually happens to
  data before it reaches an ML model. That rabbit hole led me into
  pipelines, AWS, Snowflake, ETL/ELT, real-time systems and analytics.

  verified
  ✦ AWS Certified Cloud Practitioner ............ Amazon     Aug 2026
  ✦ Generative AI Professional .................. Oracle     Jul 2025
  ✦ SC-900 Security, Compliance & Identity ...... Microsoft  Jun 2025
────────────────────────────────────────────────────────────────────────
```

## skill sets

<details open>
<summary>📁 <code>data_engineering</code></summary>
<br>
<img src="https://img.shields.io/badge/Airflow-171614?style=flat-square&logo=apacheairflow&logoColor=A8AEF5">
<img src="https://img.shields.io/badge/dbt-171614?style=flat-square&logo=dbt&logoColor=A8AEF5">
<img src="https://img.shields.io/badge/Kafka-171614?style=flat-square&logo=apachekafka&logoColor=A8AEF5">
<img src="https://img.shields.io/badge/PySpark-171614?style=flat-square&logo=apachespark&logoColor=A8AEF5">
<img src="https://img.shields.io/badge/NiFi-171614?style=flat-square&logo=apache&logoColor=A8AEF5">
<img src="https://img.shields.io/badge/Docker-171614?style=flat-square&logo=docker&logoColor=A8AEF5">
<img src="https://img.shields.io/badge/CDC%20%2F%20SCD%201%262-171614?style=flat-square">
</details>

<details>
<summary>📁 <code>cloud_and_warehouse</code></summary>
<br>
<img src="https://img.shields.io/badge/Snowflake-171614?style=flat-square&logo=snowflake&logoColor=A8AEF5">
<img src="https://img.shields.io/badge/S3-171614?style=flat-square&logo=amazons3&logoColor=A8AEF5">
<img src="https://img.shields.io/badge/Lambda-171614?style=flat-square&logo=awslambda&logoColor=A8AEF5">
<img src="https://img.shields.io/badge/Glue%20%2B%20Athena-171614?style=flat-square&logo=amazonwebservices&logoColor=A8AEF5">
<img src="https://img.shields.io/badge/PostgreSQL-171614?style=flat-square&logo=postgresql&logoColor=A8AEF5">
<img src="https://img.shields.io/badge/OCI-171614?style=flat-square&logo=oracle&logoColor=A8AEF5">
</details>

<details>
<summary>📁 <code>code_and_analysis</code></summary>
<br>
<img src="https://img.shields.io/badge/Python-171614?style=flat-square&logo=python&logoColor=A8AEF5">
<img src="https://img.shields.io/badge/SQL-171614?style=flat-square&logo=postgresql&logoColor=A8AEF5">
<img src="https://img.shields.io/badge/C%2B%2B-171614?style=flat-square&logo=cplusplus&logoColor=A8AEF5">
<img src="https://img.shields.io/badge/pandas-171614?style=flat-square&logo=pandas&logoColor=A8AEF5">
<img src="https://img.shields.io/badge/scikit--learn-171614?style=flat-square&logo=scikitlearn&logoColor=A8AEF5">
<img src="https://img.shields.io/badge/Power%20BI-171614?style=flat-square&logo=powerbi&logoColor=A8AEF5">
</details>

## projects

> *pinned to the board — click a name to open the repo, the arrow to open its page*

### [Zomato Data Pipeline + AI](https://github.com/DevrajBijpuria/Zomato-DataPiple-Ai)
`S3 → Snowflake → dbt → Gemini → Streamlit` &nbsp; *— 4.7M+ records, text-to-SQL that only ever SELECTs*

<details>
<summary>open the notebook page</summary>

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#171614','primaryTextColor':'#ece5d4','primaryBorderColor':'#A8AEF5','lineColor':'#B8B1A5','fontFamily':'monospace'}}}%%
flowchart LR
  A["S3 raw"] --> B["Snowflake RAW"] --> C["dbt staging → marts"]
  C --> D["Gemini review enrichment"] --> E["Streamlit: RAG + text-to-SQL"]
  F(["Airflow, daily"]) -.-> A
```
7 source tables, incremental dbt models with data-quality tests, Gemini tags every review by sentiment, topic and key issue.
</details>

### [Real-Time Data Pipeline](https://github.com/DevrajBijpuria/REAL-TIME-DATA-PIPELINE)
`NiFi → S3 → Snowpipe → Streams + Tasks` &nbsp; *— runs itself once started*

<details>
<summary>open the notebook page</summary>

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#171614','primaryTextColor':'#ece5d4','primaryBorderColor':'#A8AEF5','lineColor':'#B8B1A5','fontFamily':'monospace'}}}%%
flowchart LR
  A["Faker CSV"] --> B["NiFi on EC2"] --> C["S3"] -->|Snowpipe| D["customer_raw"]
  D -->|"task · SCD1"| E["customer"] -->|stream| F["task · SCD2"] --> G["customer_history"]
```
10k records per batch, Tasks every minute, full change history with `start_time`, `end_time`, `is_current`.
</details>

### [Spotify AWS Pipeline](https://github.com/DevrajBijpuria/Data_Pipeline_pro1)
`Lambda → S3 → Glue → Athena` &nbsp; *— no servers anywhere, costs nothing when idle*

<details>
<summary>open the notebook page</summary>

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#171614','primaryTextColor':'#ece5d4','primaryBorderColor':'#A8AEF5','lineColor':'#B8B1A5','fontFamily':'monospace'}}}%%
flowchart LR
  A(["CloudWatch, daily"]) --> B["Lambda: extract"] --> C["S3 raw JSON"]
  C -->|object created| D["Lambda: transform"] --> E["songs / albums / artists"] --> F["Glue → Athena"]
```
One playlist payload in, three deduplicated tables out; raw JSON archived, never overwritten.
</details>

### [NNNIDS](https://github.com/NihalGeek/NNNIDS)
`detect → respond → verify the fix` &nbsp; *— NextGen Hackathon finalist*

<details>
<summary>open the notebook page</summary>

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#171614','primaryTextColor':'#ece5d4','primaryBorderColor':'#A8AEF5','lineColor':'#B8B1A5','fontFamily':'monospace'}}}%%
flowchart LR
  A["Scapy capture"] --> B["signatures + Isolation Forest + behaviour + threat intel"]
  B --> C["risk score 0-100"] --> D["block / throttle"] --> E["verify it worked"]
  C -.WebSocket.-> F["React dashboard"]
```
7-stage hybrid detection, OS-firewall response through `netsh` / `iptables`, live dashboard.
</details>

### [Signal Desk](https://github.com/DevrajBijpuria/signal-desk)
`rule-scored news in an 1890s broadsheet` &nbsp; *— no model in the loop, ₹0 to run*

<details>
<summary>open the notebook page</summary>

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#171614','primaryTextColor':'#ece5d4','primaryBorderColor':'#A8AEF5','lineColor':'#B8B1A5','fontFamily':'monospace'}}}%%
flowchart LR
  A(["cron, 4x a day"]) --> B["fetch · dedupe · score · tag"] --> C["Netlify Blobs"] --> D["/api/news"] --> E["broadsheet"]
```
Legitimacy score from source tiers plus corroboration, with the reason printed on every story.
</details>

## contact

<a href="mailto:dbijpuria@gmail.com"><img src="https://img.shields.io/badge/email-dbijpuria%40gmail.com-000000?style=for-the-badge&labelColor=171614&color=000000&logo=gmail&logoColor=A8AEF5"></a>
<a href="https://linkedin.com/in/devraj-bijpuria"><img src="https://img.shields.io/badge/linkedin-devraj--bijpuria-000000?style=for-the-badge&labelColor=171614&logo=linkedin&logoColor=A8AEF5"></a>
<a href="https://portfoliodevraj.vercel.app/"><img src="https://img.shields.io/badge/portfolio-the%20full%20board%20%E2%86%97-000000?style=for-the-badge&labelColor=171614&logo=vercel&logoColor=A8AEF5"></a>

<br><br>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Caveat&weight=600&size=28&duration=3500&pause=2500&color=ECE5D4&background=000000&center=true&vCenter=true&width=900&height=70&lines=find+something+interesting+%E2%86%92+go+down+the+rabbit+hole+%E2%86%92+build+something+with+it" alt="find something interesting, go down the rabbit hole, build something with it">
</p>
