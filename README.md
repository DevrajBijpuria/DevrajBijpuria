<!-- Profile README for github.com/DevrajBijpuria Visual language borrowed from portfoliodevraj.vercel.app: landing type lines → CRT desktop → engineering pinboard. Every SVG in /assets is generated; edit build.py and re-run rather than hand-editing. --> <p align="center"> <a href="#about"><img src="assets/line-name.svg" width="100%" alt="DEVRAJ BIJPURIA"></a> <a href="#skill-sets"><img src="assets/line-skills.svg" width="100%" alt="SKILL SETS"></a> <a href="#projects"><img src="assets/line-projects.svg" width="100%" alt="PROJECTSSSS"></a> <a href="#contact"><img src="assets/line-contact.svg" width="100%" alt="CONTACT"></a> </p> <p align="center"><sub>Select a line to open its section, same as on <a href="https://portfoliodevraj.vercel.app/">the site</a>.</sub></p>

<a name="about"></a>

<img src="assets/about.svg" width="100%" alt="About: Devraj Bijpuria, Computer Science student at VIT Bhopal (class of 2027) building data pipelines, AWS and Snowflake systems and analytics. AWS Certified Cloud Practitioner, Oracle Generative AI Professional, Microsoft SC-900."> <br>

<a name="skill-sets"></a>

<img src="assets/line-skills.svg" width="100%" alt="SKILL SETS"> <img src="assets/skills.svg" width="100%" alt="Six skill folders on a CRT desktop"> <details> <summary>📁 <code>programming</code></summary> <br> Python, SQL, C++, PySpark </details> <details> <summary>📁 <code>data_engineering</code></summary> <br> ETL/ELT pipelines, data ingestion and transformation, Change Data Capture (CDC), SCD Type 1 and 2, Apache Airflow, Kafka, dbt, Apache NiFi, Docker </details> <details> <summary>📁 <code>cloud_aws</code></summary> <br> Amazon S3, AWS Lambda, AWS Glue, Amazon Athena, Amazon CloudWatch, EC2, Oracle Cloud Infrastructure (OCI) </details> <details> <summary>📁 <code>databases</code></summary> <br> Snowflake (Snowpipe, Streams, Tasks), PostgreSQL, data warehousing, data modeling, relational database design, window functions </details> <details> <summary>📁 <code>analytics</code></summary> <br> pandas, NumPy, data cleaning, exploratory data analysis, statistics, data visualization, Power BI </details> <details> <summary>📁 <code>machine_learning</code></summary> <br> scikit-learn, XGBoost, tree-based models and ensembles, Isolation Forest, LLM apps with Gemini (RAG, text-to-SQL) </details> <br>

<a name="projects"></a>

<img src="assets/line-projects.svg" width="100%" alt="PROJECTSSSS"> <a href="https://portfoliodevraj.vercel.app/"><img src="assets/board.svg" width="100%" alt="Engineering pinboard with five pinned projects"></a>

<a href="https://github.com/DevrajBijpuria/Zomato-DataPiple-Ai"><img src="assets/card-zomato.svg" width="100%" alt="Zomato Data Pipeline + AI: S3 to Snowflake to dbt to Gemini to Streamlit"></a>

<details> <summary><b>Open the notebook page</b></summary> <br>
COPY INTO
writes back
orchestrates
S3 raw
Snowflake RAW
dbt staging
dbt marts
Gemini enrichment
Streamlit: RAG chat
Streamlit: text-to-SQL
Airflow zomato_batch, daily
4.7M+ records across 7 tables (restaurants, users, food, menus, orders, order items, reviews).
Incremental dbt models with data-quality tests, from typed staging views to facts, dims and mart_* aggregates.
Gemini classifies every review by sentiment, topic and key issue; text-to-SQL is locked to SELECT-only queries.
<img src="assets/shots/zomato.png" width="100%" alt="Text-to-SQL Streamlit app"> </details>

<a href="https://github.com/DevrajBijpuria/REAL-TIME-DATA-PIPELINE"><img src="assets/card-realtime.svg" width="100%" alt="Real-Time Data Pipeline: NiFi to S3 to Snowpipe to Snowflake Streams and Tasks"></a>

<details> <summary><b>Open the notebook page</b></summary> <br>
PutS3Object
Snowpipe
task, SCD1
stream
task, SCD2
Faker CSV
NiFi on EC2, Docker
S3 external stage
customer_raw
customer
change-data view
customer_history
Zero manual steps once running: Snowpipe auto-ingests, two Tasks fire every minute.
SCD Type 1 keeps current state; SCD Type 2 keeps every change with start_time, end_time and is_current.
<img src="assets/shots/realtime.png" width="100%" alt="Apache NiFi flow"> </details>

<a href="https://github.com/DevrajBijpuria/Data_Pipeline_pro1"><img src="assets/card-spotify.svg" width="100%" alt="Spotify AWS Pipeline: Lambda to S3 to Glue to Athena"></a>

<details> <summary><b>Open the notebook page</b></summary> <br>
object created
CloudWatch, daily
Lambda: extract
S3 raw JSON
Lambda: transform
S3 songs / albums / artists
Glue crawler + catalog
Athena SQL
Fully serverless, so an idle day costs nothing.
One playlist payload becomes three deduplicated tables; raw JSON is archived, never overwritten.
<img src="assets/shots/spotify.jpg" width="100%" alt="Extract Lambda code"> </details>

<a href="https://github.com/NihalGeek/NNNIDS"><img src="assets/card-nnnids.svg" width="100%" alt="NNNIDS: real-time intrusion detection with automated response"></a>

<details> <summary><b>Open the notebook page</b></summary> <br>
WebSocket
Scapy capture
Features
Signatures
Isolation Forest
Behavioral baseline
Threat intel
Risk score 0-100
Block / throttle / monitor
Verify the fix
React dashboard
Hybrid 7-stage pipeline: rules, ML anomaly detection and behavioral heuristics in one pass.
Blocks IPs through the OS firewall (netsh or iptables), then measures whether the block actually worked.
NextGen Hackathon finalist.
<img src="assets/shots/nnnids.png" width="100%" alt="NNNIDS dashboard"> </details>

<a href="https://github.com/DevrajBijpuria/signal-desk"><img src="assets/card-signal-desk.svg" width="100%" alt="Signal Desk: rule-scored news in an 1890s broadsheet"></a>

<details> <summary><b>Open the notebook page</b></summary> <br>
edge-cached read
cron, 4x a day
fetch, dedupe, score, tag
Netlify Blobs
/api/news
Broadsheet front page
Every story gets a legitimacy score from source tiers plus corroboration, with the reason printed next to it.
Page loads never touch a feed, so it runs on Netlify's free tier at zero cost.
<img src="assets/shots/signal-desk.png" width="100%" alt="Signal Desk front page"> </details> <br>

<a name="contact"></a>

<img src="assets/line-contact.svg" width="100%" alt="CONTACT"> <p align="center"> <a href="mailto:dbijpuria@gmail.com"><img src="assets/btn-email.svg" width="24%" alt="Email dbijpuria@gmail.com"></a> <a href="https://linkedin.com/in/devraj-bijpuria"><img src="assets/btn-linkedin.svg" width="24%" alt="LinkedIn"></a> <a href="https://portfoliodevraj.vercel.app/"><img src="assets/btn-portfolio.svg" width="24%" alt="Portfolio"></a> <a href="https://portfoliodevraj.vercel.app/DEVRAJ_BIJPURIA_RESUME.pdf"><img src="assets/btn-resume.svg" width="24%" alt="Download résumé"></a> </p> <details> <summary><code>git log --graph</code></summary> <br> <img src="https://github-readme-activity-graph.vercel.app/graph?username=DevrajBijpuria&bg_color=000000&color=ece5d4&line=A8AEF5&point=FFFCF3&area=true&area_color=A8AEF5&hide_border=true" width="100%" alt="Contribution graph"> </details> <img src="assets/footer.svg" width="100%" alt="find something interesting, go down the rabbit hole, build something with it">
