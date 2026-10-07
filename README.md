<!-- ============================== HEADER ============================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,18,20&height=230&section=header&text=Punniyamoorthy%20K&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Python%20Backend%20Developer%20-%20REST%20APIs%20and%20Machine%20Learning&descSize=18&descAlignY=60" alt="Punniyamoorthy K - Python Backend Developer" width="100%"/>

<a href="https://github.com/punniyam26-hash">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=900&color=00D4FF&center=true&vCenter=true&repeat=true&width=720&height=40&lines=Healthcare+%26+FinTech+Backend+Engineer;I+build+APIs+that+are+fast%2C+reliable+%26+smart;Django+%7C+Flask+%7C+FastAPI+%7C+scikit-learn+%7C+LLMs;Make+it+work%2C+make+it+right%2C+make+it+fast" alt="Typing SVG" />
</a>

<br/><br/>

<img src="https://img.shields.io/badge/OPEN%20TO%20WORK-YES-2ea44f?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Open to work"/>
<img src="https://img.shields.io/badge/Chennai%2C%20India-On--site%20%7C%20Hybrid%20%7C%20Remote-0A66C2?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location"/>
<img src="https://img.shields.io/badge/Experience-2%2B%20Years-orange?style=for-the-badge&logo=python&logoColor=white" alt="Experience"/>
<img src="https://komarev.com/ghpvc/?username=punniyam26-hash&style=for-the-badge&color=blueviolet&label=PROFILE+VIEWS" alt="Profile views"/>

<br/>

<a href="https://www.linkedin.com/in/YOUR-LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:YOUR-EMAIL@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20Hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/punniyam26-hash"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>

</div>

---

## ⚡ 30-Second Summary *(for Recruiters & Hiring Managers)*

| | |
|---|---|
| **🎯 Role** | Python Backend / API Developer |
| **⏳ Experience** | 2+ years · 2 shipped products (healthcare, personal finance) |
| **🧰 Core Stack** | Django · DRF · Flask · FastAPI · PostgreSQL · MySQL · Docker · pytest |
| **🤖 AI / ML** | scikit-learn · Pandas · LangChain · ChromaDB · OpenAI embeddings |
| **🦸 Superpower** | Taking a feature from *requirements → data model → API → ML → deployment* on my own |
| **📊 Proof** | 87%+ model accuracy · 30,000+ records processed · 30% faster queries · 75%+ test coverage |
| **📍 Availability** | Open to work in Chennai (on-site / hybrid) & Remote |

---

## 👋 Hi, I'm Punniyamoorthy

I build **backend systems that are fast, reliable and smart.** Over the last 2 years I shipped REST APIs in **healthcare** (where every prediction must be explainable and auditable) and a **personal finance product** (where users want clarity, not just transaction lists), combining solid backend engineering with **Machine Learning** and **LLM-based search**.

- 🔭 **Building now:** SmartSpend, an AI-powered finance tracker
- 🌱 **Levelling up:** Django, Flask, REST design, SQL optimization, putting ML behind an API
- 💬 **Ask me about:** FastAPI, Docker, pytest, query tuning, semantic search
- 🎯 **Looking for:** Python Backend / API Developer roles where I can own features end to end

---

## 📈 Impact at a Glance

<div align="center">

| 🎯 **87%+** | 🏥 **30,000+** | ⚡ **30%** | 🧪 **75%+** | 🟢 **0** |
|:---:|:---:|:---:|:---:|:---:|
| ML model accuracy | patient records processed | faster audit queries | test coverage | downtime incidents in production |

</div>

---

## 🧩 Problems I've Solved

| Problem | What I did | Result |
|---|---|---|
| Raw patient data was too noisy for reliable predictions | Cleaned and preprocessed 30,000+ records with Pandas and NumPy | **+12% accuracy**, final model at 87%+ |
| Audit queries were slow as data grew | Designed composite indexes on MySQL | **30% faster** audit queries |
| Healthcare needs predictions that can be justified | Stored every prediction with confidence score and top risk factors | A complete **audit trail** for compliance |
| Clinical notes were hard to search by keyword | Built a semantic search layer (LangChain, ChromaDB, Sentence Transformers, OpenAI embeddings) | Search by **meaning**, not exact words |
| People don't know where their money goes | Built anomaly detection and a next-month forecast (Linear Regression) with Chart.js dashboards | Spending **insights**, not just transaction lists |

---

## 🏗️ Architecture Deep Dives

### 🏥 Patient Risk Prediction API

```mermaid
flowchart LR
    A[Client / Clinical Dashboard] -->|REST request| B[Flask API]
    B --> C[Preprocessing<br/>Pandas · NumPy · Scaler]
    C --> D[RandomForest Model<br/>Risk: Low / Medium / High]
    D --> E[(MySQL<br/>Predictions + Audit Trail)]
    B --> F[Semantic Search<br/>LangChain + ChromaDB]
    F --> G[OpenAI Embeddings]
    D -. confidence + top factors .-> B
```

### 💸 SmartSpend

```mermaid
flowchart LR
    U[User] --> V[Django Views + Auth]
    V --> P[(PostgreSQL<br/>Transactions · Budgets)]
    P --> I[Insights Engine<br/>Pandas + scikit-learn]
    I --> AD[Anomaly Detection]
    I --> NF[Next-month Forecast<br/>Linear Regression]
    P --> BT[Budget Tracking<br/>ORM Aggregation]
    AD --> CJ[Chart.js Dashboard]
    NF --> CJ
    BT --> CJ
```

<details>
<summary>🔍 <b>Sample response: how the risk API explains itself</b> <i>(illustrative)</i></summary>

```json
{
  "patient_id": "P-10234",
  "risk_level": "High",
  "confidence": 0.89,
  "top_factors": ["blood_pressure", "age", "glucose_level"],
  "audit_id": "a1b2c3d4"
}
```

</details>

---

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,django,flask,fastapi,postgres,mysql,docker,git,github,linux,postman,react,js,html,css&theme=dark" alt="Tech icons" />

</div>

<details open>
<summary><b>⚙️ Backend & Databases</b></summary>
<br/>

![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=flat-square&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![OAuth](https://img.shields.io/badge/OAuth_2.0-3C873A?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

</details>

<details open>
<summary><b>🤖 AI / ML / LLM</b></summary>
<br/>

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square)

</details>

<details open>
<summary><b>🧪 Testing & DevOps</b></summary>
<br/>

![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

</details>

<details>
<summary><b>🎨 Frontend (working knowledge)</b></summary>
<br/>

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

</details>

---

## 💼 Experience

### 🔹 Python Backend Developer · Flay High Software
**Dec 2025 – Present**

**SmartSpend:** AI-Powered Finance Tracker · `Django` `PostgreSQL` `Pandas` `scikit-learn` `Chart.js` `pytest` `Docker`

- Owned the product **end to end**: requirements, data modeling, backend, ML integration and UI
- Built an insights engine that **flags anomalous transactions** and **forecasts next-month spending** using Linear Regression
- Implemented budget tracking with Django ORM aggregation against user-defined monthly limits
- Created interactive **Chart.js dashboards** for category-wise spending breakdowns
- Designed authentication and a PostgreSQL-ready schema for transactions and budgets
- Wrote pytest suites for transaction, budget and forecasting logic; containerized the app with Docker

### 🔹 Python Backend Developer · NSEIT
**Oct 2024 – Nov 2025**

**Healthcare Patient Risk Prediction API** · `Flask` `scikit-learn` `Pandas` `MySQL` `ChromaDB` `LangChain` `OpenAI`

- Built and deployed a Flask REST API serving a **RandomForest model** that classifies patient risk (Low / Medium / High) with **87%+ accuracy**
- Preprocessed 30,000+ patient records, improving model accuracy by **12%**
- Delivered 4 REST endpoints for real-time prediction, patient history and dashboard statistics
- Added composite indexes on MySQL, cutting audit query time by **30%**
- Stored every prediction with confidence score and top risk factors, creating an **audit trail** for compliance
- Built a **semantic search layer** over clinical notes using ChromaDB, LangChain, Sentence Transformers and OpenAI embeddings
- Reached **75%+ code coverage** with unit tests, deployed to Linux production with **zero downtime incidents**

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 💸 SmartSpend
*AI-powered personal finance tracker*

- 🔍 Anomaly detection on transactions
- 📈 Next-month spending forecast
- 📊 Category-wise Chart.js dashboards
- 🐳 Dockerized and tested with pytest

`Django` `PostgreSQL` `scikit-learn` `Docker`

**[🔗 View Repository](https://github.com/punniyam26-hash/SmartSpend)**

</td>
<td width="50%" valign="top">

### 🏥 Patient Risk Prediction API
*ML-powered healthcare risk classifier*

- 🎯 87%+ accuracy RandomForest model
- 🧾 Audit trail with confidence scores
- 🧠 Semantic search over clinical notes
- ⚡ 30% faster queries via indexing

`Flask` `MySQL` `ChromaDB` `LangChain`

**[🔗 View Repository](https://github.com/punniyam26-hash/Patient-Risk-Prediction-API)**

</td>
</tr>
</table>

---

## 🎁 What I Bring to Your Team

| | |
|---|---|
| 🧭 **End-to-end ownership** | Requirements → data model → API → ML → deployment, with minimal handoffs |
| 🏭 **Production mindset** | Indexing, audit trails, testing, zero-downtime deployments |
| 🤝 **Backend + ML + LLM** | I can ship ML features without waiting for a separate AI team |
| 🏥 **Regulated-domain experience** | Healthcare and finance taught me explainability, traceability and data care |
| 💼 **Business understanding** | MBA background: I ask *why* a feature matters before I build it |

---

## 🧭 How I Work

1. **Make it work, make it right, make it fast**, in that order
2. **Measure before optimizing:** indexes, queries and models get numbers, not guesses
3. **Explainable by default:** every prediction I serve can say *why*
4. **Tests are part of the feature,** not a follow-up task
5. **Clear communication:** I write docs and PR descriptions that others can actually follow

---

## 🌱 Currently Levelling Up

- [ ] Django · Flask · REST API design
- [ ] ML in production · LLM-based semantic search
- [ ] Docker basics
- [ ] FastAPI (async endpoints, Pydantic validation)
- [ ] CI/CD pipelines (GitHub Actions)
- [ ] Redis caching and background jobs (Celery)

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=punniyam26-hash&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&rank_icon=github" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=punniyam26-hash&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&langs_count=6" alt="Top languages" />

<br/>

<img src="https://streak-stats.demolab.com?user=punniyam26-hash&theme=tokyonight&hide_border=true&background=0d1117" alt="GitHub streak" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=punniyam26-hash&bg_color=0d1117&color=00d4ff&line=2c5364&point=ffffff&area=true&area_color=203a43&hide_border=true&title_color=00d4ff" width="95%" alt="Contribution graph" />

</div>

---

## 🎓 Education

- 🎓 **MBA**: add college & year
- 🎓 **Degree**: add degree, college & year
- 📜 **Certifications**: Python, ML, FastAPI (add details)

---

## 🤝 Let's Connect

<div align="center">

**Hiring for a Python Backend / API role? Let's talk. I reply fast.**
Open to opportunities in **Chennai & Remote**.

<a href="https://www.linkedin.com/in/YOUR-LINKEDIN"><img src="https://img.shields.io/badge/CONNECT%20ON%20LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:YOUR-EMAIL@gmail.com"><img src="https://img.shields.io/badge/EMAIL%20ME-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

<br/><br/>

*"Make it work, make it right, make it fast."* ⚡

<!-- ============================== FOOTER ============================== -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,18,20&height=140&section=footer&reversal=true&text=Thanks%20for%20visiting&fontSize=26&fontColor=ffffff&fontAlignY=68" width="100%" alt="Footer"/>

</div>
