<div align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Punniyamoorthy%20K&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Python%20Backend%20Developer&descSize=20&descAlignY=60" width="100%" alt="Punniyamoorthy K - Python Backend Developer" /> <a href="https://github.com/punniyam26-hash"> <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=750&lines=Python+Backend+%7C+API+Developer;Django+%C2%B7+DRF+%C2%B7+Flask+%C2%B7+FastAPI+%C2%B7+PostgreSQL;Fraud+Detection+%26+Audit+Monitoring+Platforms;Machine+Learning+%C2%B7+LLM-based+Semantic+Search" alt="Typing SVG" /> </a>

<br/>

![Open to Work](https://img.shields.io/badge/OPEN_TO_WORK-16A34A?style=for-the-badge)
![Chennai](https://img.shields.io/badge/CHENNAI-TAMIL_NADU,_INDIA-0EA5E9?style=for-the-badge&logo=googlemaps&logoColor=white)
![Experience](https://img.shields.io/badge/EXPERIENCE-2%2B_YEARS-F59E0B?style=for-the-badge)

<br/>

<a href="https://www.linkedin.com/in/punniyamoorthy-k"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:punniyam26@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://github.com/punniyam26-hash?tab=repositories"><img src="https://img.shields.io/badge/Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" /></a>

<br/><br/>

[Summary](#-professional-summary) &nbsp;|&nbsp;
[Impact](#-impact-at-a-glance) &nbsp;|&nbsp;
[Architecture](#-architecture-deep-dives) &nbsp;|&nbsp;
[Tech Stack](#-tech-stack) &nbsp;|&nbsp;
[Experience](#-experience) &nbsp;|&nbsp;
[Dashboard](#-github-dashboard) &nbsp;|&nbsp;
[Education](#-education--certifications) &nbsp;|&nbsp;
[Contact](#-lets-connect)

</div>

---

## 🎯 Professional Summary

Python Backend Developer with **2+ years** of experience building REST APIs and data-driven backend systems in **healthcare** and **fraud detection / audit monitoring** domains, using Django, Flask, FastAPI, PostgreSQL and MySQL.

- Built an **anomaly-detection and rule-based fraud monitoring platform** with audit trails and case review workflows
- Delivered a **patient risk-prediction API** with **87%+ model accuracy**
- Cut audit query times by **30%** through schema indexing
- Maintained **70-75%+ test coverage** with pytest and unittest
- Integrated **Scikit-learn models** and **LLM-based semantic search** (ChromaDB, LangChain, OpenAI) into production services

| | |
|---|---|
| **Role** | Python Backend / API Developer |
| **Experience** | 2+ years (healthcare, fraud detection & audit monitoring) |
| **Core Stack** | Django · DRF · Flask · FastAPI · PostgreSQL · MySQL · Docker · pytest |
| **AI / ML** | Scikit-learn (Isolation Forest, RandomForest) · Pandas · NumPy · ChromaDB · LangChain · OpenAI |
| **Security** | JWT · OAuth 2.0 · Role-Based Access Control (RBAC) |
| **Location** | Chennai, Tamil Nadu, India |
| **Languages** | Tamil (Native) · English (Professional) |

---

## 📈 Impact at a Glance

<div align="center">

![Accuracy](https://img.shields.io/badge/87%25%2B-ML_ACCURACY-0EA5E9?style=for-the-badge)
![Records](https://img.shields.io/badge/30,000%2B-PATIENT_RECORDS_PROCESSED-8B5CF6?style=for-the-badge)
![Query](https://img.shields.io/badge/30%25-FASTER_AUDIT_QUERIES-16A34A?style=for-the-badge)
![Coverage](https://img.shields.io/badge/70--75%25%2B-TEST_COVERAGE-F59E0B?style=for-the-badge)
![Improvement](https://img.shields.io/badge/%2B12%25-MODEL_ACCURACY_GAIN-EC4899?style=for-the-badge)
![Downtime](https://img.shields.io/badge/ZERO-DOWNTIME_INCIDENTS-14B8A6?style=for-the-badge)

</div>

---

## 🧩 Problems I've Solved

| Problem | What I did | Result |
|---|---|---|
| Raw patient data was too noisy for reliable predictions | Cleaned and preprocessed 30,000+ records (missing values, categorical encoding, StandardScaler) | **+12%** model accuracy |
| Audit queries were slow on large data | Added composite indexes on `patient_id`, `risk_level`, `created_at` in MySQL | **30% faster** audit queries |
| Healthcare predictions had to be justified | Stored every prediction with confidence score and top risk factors | Complete audit trail for compliance |
| Clinical notes were hard to search by keyword | Built a semantic search layer (ChromaDB, LangChain, Sentence Transformers, OpenAI embeddings) | Natural-language retrieval |
| Fraud investigators were flooded with false alerts | Combined a rule engine with Isolation Forest and tuned thresholds for precision vs. recall | Fewer false positives for investigators |
| Flagged transactions needed accountability | Built an immutable audit trail of every flagged event, rule triggered, risk score and reviewer action | Explainability and audit reporting |

---

## 🏗️ Architecture Deep Dives

### 🛡️ Fraud Detection & Audit Monitoring Platform

```mermaid
flowchart TD
    A[Incoming Transactions] --> B[Django REST API<br/>JWT + RBAC]
    B --> C[Rule Engine<br/>Threshold · Velocity · Duplicate · Unusual Pattern]
    B --> D[Isolation Forest<br/>Anomaly Detection]
    C --> E{Risk Scoring}
    D --> E
    E -->|Flagged| F[Alert Triage & Case Management<br/>Assign · Notes · Resolve]
    E -->|Cleared| G[Cleared]
    F --> H[(PostgreSQL<br/>Immutable Audit Trail)]
    G --> H
    H --> I[Chart.js Dashboards<br/>Risk Trends · Alert Status]
```

### 🏥 Patient Risk Prediction API

```mermaid
flowchart TD
    A[Client / Clinical Dashboard] -->|REST request| B[Flask API<br/>4 REST endpoints]
    B --> C[Preprocessing<br/>Pandas · NumPy · StandardScaler]
    B --> D[Semantic Search<br/>LangChain + ChromaDB]
    D --> E[OpenAI Embeddings<br/>Sentence Transformers]
    C --> F[RandomForest Model<br/>Low / Medium / High]
    F --> G[(MySQL<br/>Predictions + Audit Trail)]
    D --> G
```

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Backend**

![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/Django_REST_Framework-A30000?style=flat-square&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![OAuth](https://img.shields.io/badge/OAuth_2.0-EB5424?style=flat-square&logo=auth0&logoColor=white)
![RBAC](https://img.shields.io/badge/RBAC-6366F1?style=flat-square)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Schema Design](https://img.shields.io/badge/Schema_Design-334155?style=flat-square)
![Indexing](https://img.shields.io/badge/Indexing-334155?style=flat-square)
![Query Optimization](https://img.shields.io/badge/Query_Optimization-334155?style=flat-square)

**AI / ML**

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![Sentence Transformers](https://img.shields.io/badge/Sentence_Transformers-334155?style=flat-square)
![joblib](https://img.shields.io/badge/joblib-334155?style=flat-square)

Isolation Forest · RandomForest · Logistic Regression · Anomaly Detection · Feature Engineering · Semantic Search

**Fraud & Audit**

`Rule Engines` `Risk Scoring` `Alert Triage` `Audit Trail Logging` `Case Management` `Compliance Reporting`

**Testing**

![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![unittest](https://img.shields.io/badge/unittest-3776AB?style=flat-square&logo=python&logoColor=white)
![TDD](https://img.shields.io/badge/TDD-16A34A?style=flat-square)
![Integration Testing](https://img.shields.io/badge/Integration_Testing-334155?style=flat-square)
![Code Coverage](https://img.shields.io/badge/Code_Coverage-334155?style=flat-square)

**Tools & DevOps**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Agile](https://img.shields.io/badge/Agile%2FScrum-0052CC?style=flat-square&logo=jira&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-foundational-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Frontend (working knowledge)**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)

---

## 💼 Experience

### Python Backend Developer · Flay High Software
**Dec 2025 – Present**
*Fraud Detection & Audit Monitoring Platform*
`Python` `Django REST Framework` `PostgreSQL` `Pandas` `Scikit-learn` `Docker` `pytest`

- Designed and built a fraud detection and audit monitoring backend that screens transactions in real time and flags suspicious activity for audit and compliance teams.
- Implemented a configurable rule engine (threshold, velocity, duplicate-entry and unusual-pattern checks) combined with Scikit-learn **Isolation Forest** anomaly detection to generate risk scores for each transaction.
- Engineered features with Pandas and NumPy from historical transaction data and tuned alert thresholds to balance precision and recall, reducing false-positive alerts for investigators.
- Built alert triage and case management APIs covering alert assignment, status tracking, investigator notes and resolution, with **RBAC** and **JWT** authentication.
- Created an immutable audit trail that logs every flagged event, rule triggered, risk score and reviewer action, supporting explainability and audit reporting.
- Developed monitoring dashboards and summary reports for flagged transactions, risk trends and alert status using Chart.js.
- Wrote pytest suites for rules, scoring and alert workflows; containerized the application with Docker for consistent deployment.

### Python Backend Developer · NSEIT
**Oct 2024 – Nov 2025**
*Healthcare Patient Risk Prediction API*
`Flask` `Scikit-learn` `Pandas` `NumPy` `MySQL` `ChromaDB` `LangChain` `OpenAI API`

- Built and deployed a Flask REST API serving a Scikit-learn **RandomForest** model that classifies patient risk as Low, Medium or High with **87%+ accuracy** on test data, exposed through 4 REST endpoints for real-time prediction, patient history and dashboard statistics.
- Cleaned and preprocessed **30,000+ patient records** with Pandas and NumPy (missing-value handling, categorical encoding, StandardScaler), improving model accuracy by **12%**.
- Optimized the MySQL schema with composite indexes on `patient_id`, `risk_level` and `created_at`, reducing audit query response time by **30%**.
- Stored every prediction with its confidence score and top risk factors in MySQL, creating an audit trail for compliance reporting and model performance monitoring.
- Built a semantic search layer over clinical notes and patient records using ChromaDB, LangChain, Sentence Transformers and OpenAI embeddings for natural-language retrieval.
- Reached **75%+ code coverage** with unittest suites and deployed services to a Linux production environment with **zero downtime incidents**.

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ Fraud Detection & Audit Monitoring
*Rule engine + ML anomaly detection*

- Configurable rules: threshold, velocity, duplicates
- Isolation Forest risk scoring
- Alert triage, case management, RBAC + JWT
- Immutable audit trail
- Chart.js dashboards
- Dockerized and tested with pytest

`Django REST` `PostgreSQL` `Scikit-learn` `Docker`

<a href="https://github.com/punniyam26-hash?tab=repositories">View Repository →</a>

</td>
<td width="50%" valign="top">

### 🏥 Patient Risk Prediction API
*ML-powered healthcare risk classifier*

- 87%+ accuracy RandomForest model
- Predictions stored with confidence scores
- Semantic search over clinical notes
- Composite-indexed MySQL (30% faster queries)
- 75%+ test coverage with unittest

`Flask` `Scikit-learn` `MySQL` `ChromaDB` `LangChain`

<a href="https://github.com/punniyam26-hash?tab=repositories">View Repository →</a>

</td>
</tr>
</table>

---

## 🤝 What I Bring to Your Team

| | |
|---|---|
| **End-to-end ownership** | From requirements to data model, API, ML integration and deployment |
| **Production mindset** | Indexing, audit trails, RBAC, testing and zero-downtime deployments |
| **Regulated-domain experience** | Healthcare and fraud/audit work taught me explainability, traceability and data care |
| **Business understanding** | MBA background (Business Management & Operations) |

---

## 📊 GitHub Dashboard

<div align="center">

<a href="https://github.com/punniyam26-hash">
  <img height="180" alt="GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=punniyam26-hash&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github" />
</a>
<a href="https://github.com/punniyam26-hash">
  <img height="180" alt="Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=punniyam26-hash&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</a>

<br/>

<img width="98%" alt="GitHub Streak" src="https://streak-stats.demolab.com/?user=punniyam26-hash&theme=tokyonight&hide_border=true&border_radius=10" />

<br/>

<img width="98%" alt="Contribution Activity Graph" src="https://github-readme-activity-graph.vercel.app/graph?username=punniyam26-hash&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20Activity" />

<br/>

<img width="98%" alt="GitHub Trophies" src="https://github-profile-trophy.vercel.app/?username=punniyam26-hash&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7&margin-w=8" />

</div>

---

## 🎓 Education & Certifications

| | |
|---|---|
| **MBA**, Business Management & Operations | Anna University, Chennai · 2022 – 2024 |
| **B.Com**, Commerce, Accounting & Business Studies | Bharathidasan University · 2019 – 2022 |
| **Certification** | Python, React, FastAPI (Udemy, 2024) |
| **Languages** | Tamil (Native) · English (Professional) |

---

## 🤝 Let's Connect

<div align="center">

**Hiring for a Python Backend / API role? Let's talk.**
Open to opportunities in **Chennai** (on-site / hybrid) & **Remote**.

<a href="mailto:punniyam26@gmail.com"><img src="https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://www.linkedin.com/in/punniyamoorthy-k"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

</div>

<!-- ===================== FOOTER ===================== -->

<div align="center">

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&italic=true&size=16&duration=4000&pause=1500&color=94A3B8&center=true&vCenter=true&width=600&lines=%22Make+it+work%2C+make+it+right%2C+make+it+fast.%22" alt="Quote" />

<br/>

<img src="https://komarev.com/ghpvc/?username=punniyam26-hash&label=Profile+Views&color=0e75b6&style=flat-square" alt="Profile views" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer&text=Thanks%20for%20visiting!&fontSize=22&fontColor=ffffff&fontAlignY=70" width="100%" alt="Footer" />

</div>



intha code la enakku tailwind css and more code add panni super ah oru full code return  kodu
