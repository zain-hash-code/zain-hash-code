<div align="center">

<!-- Hero Banner -->
<img src="https://capsule-render.vercel.app/api?type=venom&color=gradient&customColorList=6,11,20&height=180&section=header&text=&fontSize=0&animation=twinkling" width="100%"/>

# Zain Ul Abideen

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&duration=3000&pause=1200&color=0CDA62&center=true&vCenter=true&random=false&width=700&height=50&lines=%24+whoami;Zain+Ul+Abideen;AI+Engineer+%26+Software+Engineer;Building+Production+RAG+%26+Multi-Tenant+Systems;Architecting+LLM+Apps%2C+pgvector+%26+Qdrant;Shipping+Systems+with+Measurable+Impact)](https://github.com/zain-hash-code)

### ⚡ AI Engineer & Software Engineer
**Building Production LLMs, Multi-Tenant SaaS & Data Architectures**

<br/>

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zainulabiedeen/)
[![Email](https://img.shields.io/badge/-Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zainulabideen78@outlook.com)
[![Followers](https://img.shields.io/github/followers/zain-hash-code?label=Follow&style=for-the-badge&color=0CDA62&labelColor=1a1b27&logo=github)](https://github.com/zain-hash-code?tab=followers)
![Visitors](https://komarev.com/ghpvc/?username=zain-hash-code&color=0CDA62&style=for-the-badge&label=VISITORS)

</div>

---

## 🧬 About Me

```python
# Production RAG & Vector Intelligence Pipeline
async def query_intelligence(query: str, tenant_id: str) -> Response:
    embeddings = await embed_model.aembed(query)
    context = await qdrant.search(
        collection="tenant_knowledge",
        query_vector=embeddings,
        query_filter={"tenant_id": tenant_id},
        limit=5
    )
    return await llm.agenerate(query=query, context=context)
```

* 🇵🇰 Based in **Lahore, Pakistan**
* 🧠 **AI Engineer & Software Engineer** with **3+ years** designing, building, and deploying production systems
* ⚡ Deep expertise in **LLM applications, RAG pipelines, Document AI, Text-to-SQL, and vector retrieval**
* 🏗️ Proven track record building **multi-tenant SaaS platforms, automated financial engines & real-time analytics**
* 📈 Shipped systems delivering **$30M+ transaction pipelines, 60% operational overhead cuts, and 333% growth in acquisitions**
* 📨 Reach me directly at **zainulabideen78@outlook.com**
* 🟢 **Open to work** — ready to build scalable, intelligent products!

---

## 🚀 Featured Systems & Production Projects

### 📊 [Quanta](https://quanta.arithmiks.com) — Multi-Tenant AI BI Platform (Text-to-SQL)
> Conversational BI SaaS turning natural-language questions into validated SQL, live charts, and interactive dashboards without requiring manual SQL queries.

* **AST Security & Mutation Blocking:** Model-generated SQL parsed via `sqlglot` AST; mutation nodes strictly rejected inside read-only transactions to protect production databases.
* **Secure Remote Tunneling:** SSH bastion with asymmetric trust & public-host SSRF defenses to securely query private-subnet databases.
* **Cost Optimization:** Compact schema serialization reducing LLM planning-stage token payload by **~60%**.
* **Stack:** `FastAPI` • `React 19` • `TypeScript` • `SQLAlchemy 2.0` • `PostgreSQL 16` • `sqlglot` • `OpenAI / Gemini / Groq` • `Docker`

---

### 📄 [SBA Loans HQ / Virtual BDA](https://virtualbda.com) — AI Loan Portal & Document Automation
> Multi-tenant FinTech platform managing the entire loan lifecycle from inbound lead capture to funded deal, with AI embedded at every stage.

* **AI Lead Scoring:** Gemini-powered classifier scoring leads (0–100) with explainable quality and spam indicators.
* **2-Phase Document OCR:** AWS Textract + Gemini pipeline for automated document classification, structured data extraction, and audit findings.
* **AI Deal Master Summary:** Synthesizes multi-document financials into an underwriting credit memo with risk and collateral analysis.
* **Impact:** **60% reduction** in operational overhead, **30% faster** loan processing, **25% revenue growth**, and **100% visibility** into case status.
* **Stack:** `Django REST Framework` • `Google Gemini` • `AWS Textract` • `PostgreSQL` • `Celery + Redis` • `DocuSeal` • `Docker`

---

### 💳 [Mr Seller Note](https://mrsellernote.com) — FinTech Loan & Stripe Automation
> Private lending automation platform replacing manual spreadsheet tracking with a comprehensive automated financial calculation and payment engine.

* **Automated Fund Splitting:** Stripe Connect handles multi-party payouts (borrower → seller → referral commission → platform fees) in a single flow.
* **Amortization Engine:** Exact principal and interest calculations per installment with real-time running ledger updates.
* **Multi-Role Portals:** Scoped dashboards for Sellers, Borrowers, Referrals, and Admins.
* **Stack:** `Next.js` • `Django REST Framework` • `PostgreSQL` • `Stripe Connect` • `Celery` • `AWS EC2`

---

### 🏗️ [EasyBar](https://easybar.co.il) — Rebar CAD & Manufacturing Platform
> End-to-end industrial platform automating iron rebar design, quotations, and confirmed ordering for the construction industry.

* **Interactive 2D Drafting Engine:** Built with `Konva.js` for parametric sketching of bars, nets, and cages with real-time measurement feedback.
* **Automated Production Tickets:** Machine vendors receive automated, production-ready tickets directly from order submissions.
* **Recognition & Scale:** Generated **$30M+** in potential orders in year 1, **1,000+ active users** in month 1, and selected for the **Contech Incubator**.
* **Stack:** `React.js` • `Django` • `Konva.js` • `PostgreSQL` • `AWS Lambda + EC2` • `Docker`

---

### 🚗 Swerv Auto — Dealership Market Intelligence & Sourcing
> Automotive intelligence platform leveraging Open Car Data (OCD), automated scraping, and market analytics for dealership inventory acquisition.

* **Automated Data Harvesting:** AWS Lambda + Selenium workers for continuous data harvesting, sync, and automated outreach via SendGrid.
* **Sales Prospects Module:** Algorithms analyzing vehicle market patterns to surface high-margin inventory acquisition leads.
* **Impact:** **333% surge** in private-party acquisitions, **47% increase** in customer traffic, **12% higher** gross sales.
* **Stack:** `Next.js` • `Django` • `Selenium` • `PostgreSQL` • `AWS Lambda + RDS + S3` • `SendGrid`

---

### 🎙️ [Whisper Audio Transcript](https://github.com/zain-hash-code/whisper-audio-transcript) — Speech-to-Text AI Pipeline
> Modular Python pipeline utilizing OpenAI Whisper for accurate speech-to-text audio processing.

* **Capabilities:** High-fidelity multi-lingual transcription, support for various audio formats, and clean CLI execution.
* **Stack:** `Python 3.11` • `OpenAI Whisper` • `PyTorch`

---

## 🧰 Technical Arsenal

| Category | Technologies & Tools |
|---|---|
| **AI / ML & LLMs** | `OpenAI` • `Anthropic Claude` • `Google Gemini` • `LangChain` • `LlamaIndex` • `Hugging Face` • `OpenAI Whisper` • `sqlglot (AST)` |
| **Vector Databases** | `pgvector` • `Qdrant` • `Pinecone` • `ChromaDB` |
| **Backend & APIs** | `Python 3.11` • `FastAPI` • `Django` • `Django REST Framework` • `SQLAlchemy 2.0` • `Celery` • `Pytest` • `Nginx` • `Gunicorn` |
| **Frontend & UI** | `Next.js 15` • `React 19` • `TypeScript` • `JavaScript` • `Tailwind CSS v4` • `Konva.js (2D Canvas)` • `Redux Toolkit` |
| **Databases & Caching** | `PostgreSQL 16` • `MySQL` • `Redis` • `SQLite` • `RabbitMQ` |
| **Cloud & DevOps** | `AWS (EC2, S3, RDS, Lambda, Textract, SQS)` • `Docker` • `GitHub Actions` • `Linux` • `Selenium` • `Stripe Connect` |
| **Developer Tools** | `Git` • `VS Code` • `Postman` • `Swagger` • `DBeaver` • `Jira` |

---

## 🏆 GitHub Trophies

<div align="center">

[![Trophies](https://github-profile-trophy.vercel.app/?username=zain-hash-code&theme=darkhub&no-frame=true&no-bg=true&column=7&margin-w=10&margin-h=10)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 📊 The Numbers

<div align="center">

[![Zain's Streak](https://github-readme-streak-stats.herokuapp.com/?user=zain-hash-code&theme=dark&hide_border=true&background=0D1117&ring=0CDA62&fire=FF6E40&currStreakLabel=0CDA62&sideLabels=C9D1D9&dates=8B949E&currStreakNum=C9D1D9&sideNums=C9D1D9&stroke=0CDA6233)](https://github.com/DenverCoder1/github-readme-streak-stats)

<br/>

[![Zain's GitHub Stats](https://github-readme-stats.vercel.app/api/?username=zain-hash-code&show_icons=true&include_all_commits=true&count_private=true&theme=react&hide_border=true&bg_color=0D1117&title_color=0CDA62&icon_color=FF6E40&text_color=C9D1D9)](https://github.com/anuraghazra/github-readme-stats)
[![Zain's Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=zain-hash-code&langs_count=8&layout=compact&theme=react&hide_border=true&bg_color=0D1117&title_color=0CDA62&icon_color=FF6E40&text_color=C9D1D9)](https://github.com/anuraghazra/github-readme-stats)

<br/>

[![Zain's Activity Graph](https://github-readme-activity-graph.vercel.app/graph/?username=zain-hash-code&bg_color=0D1117&color=0CDA62&line=FF6E40&point=FFFFFF&area=true&area_color=0CDA6244&hide_border=true&custom_title=Contribution%20Graph)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## 🧪 Currently Exploring & Expanding

| Technology | Status | Focus Area |
|---|---|---|
| **Go** | 🟡 Exploring | High-concurrency microservices & network tooling |
| **Kubernetes** | 🟡 Scaling | Container orchestration & cloud-native deployments |
| **Terraform** | 🟡 Tinkering | Infrastructure as Code (IaC) on AWS |
| **GraphQL** | 🟢 Comfortable | Flexible client querying & schema-driven APIs |
| **React 19** | 🟢 Production | Modern frontend UI architecture & Server Components |

---

## 💭 Engineering Philosophy

```text
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│   " Make it work, make it right, make it fast.                  │
│     In that order. Always. "                                    │
│                                               — Kent Beck       │
│                                                                 │
│   → Ship early, iterate often                                   │
│   → Vector search without good chunking is just noisy math      │
│   → An untested API is a broken API you haven't found yet       │
│   → If the deploy process scares you, automate it               │
│   → Good architecture > clever code                             │
│   → Logs, metrics, and evaluations are not optional             │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

<div align="center">

[![Random Dev Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark)](https://github.com/piyushsuthar/github-readme-quotes)

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zainulabiedeen/)
[![Email](https://img.shields.io/badge/-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zainulabideen78@outlook.com)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/zain-hash-code)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%" />

[![Footer](https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&duration=3000&pause=2000&color=8B949E&center=true&vCenter=true&width=480&lines=Thanks+for+visiting!+%F0%9F%91%8B+Let's+build+something+intelligent+together.)](https://github.com/zain-hash-code)

</div>
