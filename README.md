# Sergi Japharidze
_Software engineer / Data scientist from Georgia_ <br>
[Email](mailto:sergi.japharidze@gmail.com) / [LinkedIn](https://www.linkedin.com/in/sergi-japharidze-66ab4583/) / [GitHub](https://github.com/Japharidze/) <br><br>
## 👩🏼‍💻 Work Experience
**Freelancer** @ [Toptal](https://www.toptal.com/developers/resume/sergi-japharidze#QvPmEp) _(Aug 2026 - present)_ <br>
**Freelancer** @ [Upwork](https://www.upwork.com/freelancers/~01ec363d8d634666d4?viewMode=1) _(Nov 2021 - present)_ <br>
**Deputy Head of Customer Caring Direction** @ [BOG](https://bankofgeorgia.ge/ka/retail) _(Sep 2024 - Mar 2026)_ <br>
**Head of Data Analysis Unit** @ [BOG](https://bankofgeorgia.ge/ka/retail) _(Mar 2019 - Sep 2024)_ <br>
**Data Scientist** @ [BOG](https://bankofgeorgia.ge/ka/retail) _(Mar 2018 - Mar 2019)_ <br>
One of the top banking systems in Georgia
**Data Analyst** @ [112 Georgia](https://112.gov.ge/?page_id=3136https://112.gov.ge/lang=en) _(Sep 2015 - Mar 2018)_ <br>
**ASP.NET MVC Developer** @ [112 Georgia](https://112.gov.ge/?page_id=3136https://112.gov.ge/lang=en) _(Aug 2014 - Sep 2015)_ <br>
Emergency response center of Georgia
<br><br>
    
## 📌 Projects
**Palimpsest — SEC Filings Research Agent** @ [Live](https://palimpsest.up.railway.app/) / [GitHub](https://github.com/Japharidze/palimpsest) <br>
Agentic research system over SEC EDGAR filings. Financial figures come from XBRL and deterministic code; a language model reads only prose, comparing risk factors and MD&A language across quarters to report what changed. Every claim is cited to a source filing and the citation is checked against the filing before the answer is returned, so an unsupported claim is flagged rather than shipped. Includes an incremental EDGAR ingestion pipeline, an XBRL fact warehouse, a golden evaluation set scoring retrieval and generation separately, and a web interface with agent traces and an eval dashboard. <br>
**_Technologies used:_** Python, [LangGraph](https://langchain-ai.github.io/langgraph/), Postgres, [dbt](https://www.getdbt.com/), FastAPI, React, vector search, LLM APIs <br>
**_Research:_** [RAG](https://en.wikipedia.org/wiki/Retrieval-augmented_generation), Agent Orchestration, LLM Evaluation, [XBRL](https://en.wikipedia.org/wiki/XBRL) <br>
**Google Rank Tracker** @ [Upwork](https://www.upwork.com/freelancers/~01ec363d8d634666d4?viewMode=1) <br>
Automated first-page and map-pack rank tracking for an SEO agency, replacing a manual quarterly process across thousands of keywords. Scheduled SERP collection with per-client location targeting, conservative business matching (domain for organic; name plus a second signal for map pack), explicit Found / Not Found / Failed / Review statuses so an uncertain result is never recorded as fact, and results written back to the client's spreadsheets. <br>
**_Technologies used:_** Python, SERP APIs, [Google Sheets API](https://developers.google.com/sheets/api), Google Maps API <br>
**_Research:_** Data Extraction, Entity Matching <br>
**RTTM — Real-Time Transaction Monitoring** @ [BOG](https://bankofgeorgia.ge/) <br>
Real-time monitoring, detection and alerting system embedded in Georgia's country-scale card transaction processing, running 24/7. Focused on acquirer-side fraud: Spark scored moving windows of merchant and POS-terminal behavior from the Kafka transaction stream, combining analytical rules with machine learning models. Merchant reference data from Oracle was resolved into a single merchant entity (several identifiers, many terminals, same or different MCC codes) and cached in Redis to keep the live path fast. Halted transactions were handled through a staff-facing product (React, FastAPI, Postgres). Details under NDA. <br>
**_Technologies used:_** Python, FastAPI, [Kafka](https://kafka.apache.org/), Spark, Postgres, Oracle, Redis <br>
**_Research:_** Entity Resolution, Real-Time Stream Processing, Fraud Detection <br>
**rift-mmm — Research Prototype** @ [GitHub](https://github.com/Japharidze/rift-mmm) <br>
Tested whether taste in video games a player already knows can point a newcomer to League of Legends champions, by mapping both into one micro / meso / macro space. An LLM labelling pipeline scored every champion and game, validated against hand-set anchors, with versioned prompts, measured test-retest noise, and anchor regression tests that fail a run when it drifts. Crawled champion mastery for 10,000 ranked players via the Riot API and tested whether real champion pools show taste beyond popularity against null models that preserve popularity and pool size, replicated across regions, eras and tiers. Decision rules were fixed before each experiment. Taste structure is real and replicates, but the labelled space captured only part of it, and the final family-matching rule did not beat a popularity baseline, so the project ended with a negative result, documented as such. <br>
**_Technologies used:_** Python, Postgres, LLM APIs, [Riot API](https://developer.riotgames.com/), FastAPI, React <br>
**_Research:_** LLM Labelling & Evaluation, [Null Models](https://en.wikipedia.org/wiki/Null_model), Replication, [Pre-registration](https://en.wikipedia.org/wiki/Preregistration_(science)), Clustering <br>
**Migration/ETL** @ [BOG](https://bankofgeorgia.ge/) <br>
Platform for huge data migration. ETL pipeline tasks automation <br>
**_Technologies used:_** Python, [Apache Airflow](https://airflow.apache.org/) <br>
**_Research:_** Data Engineering <br>
**Hashing & Clustering** @ [Upwork](https://www.upwork.com/freelancers/~01ec363d8d634666d4?viewMode=1) <br>
Probably the biggest challenge I've ever faced. Deep journey of handling huge amount of data sources and create data transformations to meet the need of categorizing and managing the insights. <u>Details under NDA</u> <br>
**_Technologies used:_** Python, AWS, Heroku, Postgres <br>
**_Research:_** [Hashing](https://en.wikipedia.org/wiki/Hash_function), [Clustering](https://en.wikipedia.org/wiki/Cluster_analysis) <br>
**Live Dashboard** @ [Upwork](https://www.upwork.com/freelancers/~01ec363d8d634666d4?viewMode=1) <br>
Visualization platform to monitor the process of trading bot's financial contributions <br>
**_Technologies used:_** Python, [Dash](https://plotly.com/dash/), AWS, Heroku, Postgres <br>
**Model Evaluation Dashboard** @ [Upwork](https://www.upwork.com/freelancers/~01ec363d8d634666d4?viewMode=1) <br>
Visualization platform for exploring&testing financial model performances with different parameters <br>
**_Technologies used:_** Python, [Bokeh](https://bokeh.org/), AWS, Heroku <br>
**Warehouse Automation** @ [Upwork](https://www.upwork.com/freelancers/~01ec363d8d634666d4?viewMode=1) <br>
Physical prototype for a revolutionizing warehouse automation product. <u>Details under NDA</u> <br>
**_Technologies used:_** Python, [pygame](https://www.pygame.org/news) <br>
**_Research:_** [Graph Traversal](https://en.wikipedia.org/wiki/Graph_traversal), [Iterative Deepening](https://en.wikipedia.org/wiki/Iterative_deepening_depth-first_search)<br>
**Incident Management System** @ [BOG](https://bankofgeorgia.ge/) <br>
Full-stack case management platform that replaced spreadsheet-based review. Analysts previously worked through Excel exports of alerts produced by rules and models, looked each case up in separate banking software, and recorded their findings in personal files. The platform brings it all into one place: cases are generated and assigned in the system, alerts are sent automatically, and every review outcome is captured as structured data in Oracle. That removed the manual hand-offs and the unstructured results, so outcomes can be tracked and analyzed <br>
**_Technologies used:_** Python, Flask, React <br>
**_Research:_** Workflow Automation, Case Management <br>
**Staff profiling platform** @ [BOG](https://bankofgeorgia.ge/) <br>
Internal platform that consolidates employee information scattered across 8 data sources (MSSQL, Oracle, file servers/S3, APIs) into evaluation-ready datasets for the bank's internal control function. Scheduled Celery and Airflow jobs handled data gathering and migration, and a Django web application gave reviewers one place to work. I also maintained the pipelines and the platform.
Technologies used: Python, Django, Celery, Airflow, MSSQL, Oracle, AWS S3, HTML/CSS/JS
Research: Data Integration, Internal Control <br>
**_Technologies used:_** Python, Django, [Celery](https://docs.celeryq.dev/en/stable/getting-started/introduction.html), HTML/CSS/JS <br>
**_Research:_** [CRM](https://en.wikipedia.org/wiki/Customer_relationship_management) <br>
**Flask Scheduler** @ [BOG](https://bankofgeorgia.ge/) <br>
Reporting service + Automation/scheduling of Python/SQL jobs<br>
**_Technologies used:_** Python, Flask, [APScheduler](https://apscheduler.readthedocs.io/en/3.x/), HTML/CSS/JS <br>
**Sentiment Analysis/LDA** @ [BOG](https://bankofgeorgia.ge/) <br>
Topic modeling and Sentiment analysis on feedback data to define client satisfactory respectively to the topics <br>
**_Technologies used:_** Python, nltk, gensim <br>
**_Research:_** NLP, LDA <br>
**Credit Risk Models** @ [BOG](https://bankofgeorgia.ge/) <br>
Scoring models for different banking products to predict probability of default in order to make lending process (semi)automatic <br>
**_Technologies used:_** Python, xgboost, sci-kit learn <br>
**_Research:_** Data Science, Machine Learning, [xgboost](https://xgboost.readthedocs.io/en/stable/) <br>
**Shift management** @ [112 Georgia](https://112.gov.ge/?page_id=3136https://112.gov.ge/lang=en) <br>
Define&Monitoring KPI parameters for the call center. Automate system for 24/7 live monitoring of workload and call distribution, then adjusting shifts to meet the optimized handle time. <br>
**_Technologies used:_** Python, SQL <br>
**_Research:_** [Erlang Statistic](https://en.wikipedia.org/wiki/Erlang_distribution), Statistical Analysis, [Queueing Theory](https://en.wikipedia.org/wiki/Queueing_theory) <br>
**Task manager** @ [112 Georgia](https://112.gov.ge/?page_id=3136https://112.gov.ge/lang=en) <br>
In-house task management system. <br>
**_Technologies used:_** ASP.NET MVC C#, IBM/SQL, HTML/CSS/JS <br>
**User registration/login system** @ [112 Georgia](https://112.gov.ge/?page_id=3136https://112.gov.ge/lang=en) <br>
User profiling system for existing platform <br>
**_Technologies used:_** ASP.NET MVC C#, IBM/SQL, HTML/CSS/JS <br>
<br><br>
  
## 💬 Languages
🇺🇸 **English**: Fluent (B2+) <br>
<br><br>
## 👩🏼‍🎓 Education
**Executive MBA** <br>
[Grenoble École de Management](https://en.grenoble-em.com/) - Grenoble, France (Nov 2024 - Mar 2027) <br><br>
**Master of Mathematics** <br>
[Tbilisi State University](https://www.tsu.ge/en) - Tbilisi, Georgia (Sep 2019 - May 2021) <br><br>
**Bachelor of Mathematics and Computer Science** <br> 
[Tbilisi State University](https://www.tsu.ge/en) - Tbilisi, Georgia (Sep 2014 - May 2018) <br>
