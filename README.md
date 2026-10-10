<!-- ════════════════════════════════════════════════════════════════════ -->
<!--                     ZAIN UL ABIDEEN — PROFILE README              -->
<!-- ════════════════════════════════════════════════════════════════════ -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&color=gradient&customColorList=6,11,20&height=180&section=header&text=&fontSize=0&animation=twinkling" width="100%"/>
</p>

<h1 align="center">
  <a href="https://github.com/zain-hash-code">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=27&duration=3000&pause=1200&color=0CDA62&center=true&vCenter=true&random=false&width=700&height=50&lines=%24+whoami;Zain+Ul+Abideen;AI+Engineer+%26+Software+Engineer;Building+Production+RAG+%26+Multi-Tenant+Systems;Architecting+LLM+Apps%2C+pgvector+%26+Qdrant;Shipping+Systems+with+Measurable+Impact" alt="Typing" />
  </a>
</h1>

<h3 align="center">
  <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30">
  AI Engineer & Software Engineer · Production LLMs, Multi-Tenant SaaS & Data Architectures
  <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30">
</h3>

<br/>

<!-- Social badges -->
<p align="center">
  <a href="https://www.linkedin.com/in/zainulabiedeen/">
    <img src="https://img.shields.io/badge/-Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  &#8287;
  <a href="mailto:zainulabideen78@outlook.com">
    <img src="https://img.shields.io/badge/-Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  &#8287;
  <a href="https://github.com/zain-hash-code?tab=followers">
    <img src="https://img.shields.io/github/followers/zain-hash-code?label=Follow&style=for-the-badge&color=0CDA62&labelColor=1a1b27&logo=github" alt="Followers"/>
  </a>
  &#8287;
  <img src="https://komarev.com/ghpvc/?username=zain-hash-code&color=0CDA62&style=for-the-badge&label=VISITORS" alt="Views"/>
</p>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<br/>

<!-- ═══════════════════════════════ ABOUT ═══════════════════════════════ -->

<details open>
  <summary><h2>🧬 &nbsp;About Me</h2></summary>

  <img align="right" width="280" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcDQ5Y2F0ZW1rbWluOGxydXIyZjA1cnJ0bnlndmswYmVkNHpwcndhdiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/qgQUggAC3Pfv687qPC/giphy.gif" alt="Coding GIF"/>

  <br/>

  - 🇵🇰 Based in **Lahore, Pakistan**
  - 🧠 **AI Engineer & Software Engineer** with **3+ years** designing and shipping production systems
  - ⚡ Deep expertise in **LLM applications, RAG pipelines, Document AI, Text-to-SQL, and vector retrieval**
  - 🏗️ Proven track record building **multi-tenant SaaS platforms, automated financial engines & real-time analytics**
  - 📈 Shipped systems delivering **$30M+ transaction pipelines, 60% operational overhead cuts, and 333% growth in acquisitions**
  - 📨 Reach me directly at **zainulabideen78@outlook.com**
  - 🟢 **Open to work** — ready to build scalable, intelligent products!

  <br/>

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

  <br clear="right"/>

</details>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- ════════════════════════════ FEATURED PROJECTS ═════════════════════ -->

<details open>
  <summary><h2>🚀 &nbsp;Featured Systems & Production Projects</h2></summary>
  <br/>

  <table>
    <!-- Project 1: Quanta -->
    <tr>
      <td width="55%" valign="top">
        <h3>📊 Quanta — Multi-Tenant AI BI Platform (Text-to-SQL)</h3>
        <p>
          <b>Conversational BI SaaS</b> that turns plain-English questions into validated SQL, live charts, and interactive dashboards without requiring SQL knowledge.
        </p>
        <ul>
          <li><b>Security & AST Validation:</b> Model-generated SQL parsed via <code>sqlglot</code> AST; mutation nodes strictly blocked inside read-only transactions.</li>
          <li><b>Secure Remote Tunneling:</b> SSH bastion with asymmetric trust & public-host SSRF prevention to query private databases.</li>
          <li><b>Cost Optimization:</b> Compact schema serialization reducing LLM planning-stage token payload by <b>~60%</b>.</li>
        </ul>
        <p>
          <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
          <img src="https://img.shields.io/badge/React_19-20232a?style=flat-square&logo=react&logoColor=61DAFB" />
          <img src="https://img.shields.io/badge/SQLAlchemy_2.0-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" />
          <img src="https://img.shields.io/badge/PostgreSQL_16-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
          <img src="https://img.shields.io/badge/OpenAI_%2F_Gemini_%2F_Groq-412991?style=flat-square" />
        </p>
        <p>
          🔗 <i><a href="https://quanta.arithmiks.com" target="_blank">quanta.arithmiks.com</a></i>
        </p>
      </td>
      <td width="45%" valign="top">
        <h3>⚡ Key Impact</h3>
        <br/>
        <p>
          🎯 <b>60% drop</b> in LLM planning token costs<br/>
          🔒 <b>100% read-only AST enforcement</b> preventing write injections<br/>
          🏢 <b>Multi-tenant</b> per-org AI credit limits & isolated workspaces
        </p>
      </td>
    </tr>

    <!-- Project 2: SBA Loans HQ -->
    <tr>
      <td width="55%" valign="top">
        <h3>📄 AI-Powered Loan Portal & Document Automation</h3>
        <p>
          <b>Multi-Tenant FinTech SaaS</b> managing the entire loan lifecycle from lead qualification to funded deal with embedded AI across every stage.
        </p>
        <ul>
          <li><b>AI Lead Scoring:</b> Gemini-powered classifier scoring inbound leads (0–100) with explainable quality/spam indicators.</li>
          <li><b>2-Phase Document OCR:</b> AWS Textract + Gemini pipeline for automated document classification, extraction, and anomaly auditing.</li>
          <li><b>AI Deal Master Summary:</b> Synthesizes multi-document financials into an underwriting credit memo with risk analysis.</li>
        </ul>
        <p>
          <img src="https://img.shields.io/badge/Django_REST-092E20?style=flat-square&logo=django&logoColor=white" />
          <img src="https://img.shields.io/badge/Google_Gemini-8E75C2?style=flat-square&logo=google&logoColor=white" />
          <img src="https://img.shields.io/badge/AWS_Textract-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" />
          <img src="https://img.shields.io/badge/Celery_+_Redis-37814A?style=flat-square&logo=celery&logoColor=white" />
          <img src="https://img.shields.io/badge/DocuSeal-2496ED?style=flat-square" />
        </p>
        <p>
          🔗 <i><a href="https://virtualbda.com" target="_blank">virtualbda.com</a></i>
        </p>
      </td>
      <td width="45%" valign="top">
        <h3>⚡ Key Impact</h3>
        <br/>
        <p>
          📉 <b>60% reduction</b> in operational overhead<br/>
          ⚡ <b>30% faster</b> loan processing cycle<br/>
          📈 <b>25% increase</b> in revenue growth<br/>
          👁️ <b>100% visibility</b> into case & document status
        </p>
      </td>
    </tr>

    <!-- Project 3: Mr Seller Note -->
    <tr>
      <td width="55%" valign="top">
        <h3>💳 Mr Seller Note — FinTech Loan & Stripe Automation</h3>
        <p>
          <b>Private lending automation platform</b> replacing spreadsheet loan tracking with an automated financial calculation and payment engine.
        </p>
        <ul>
          <li><b>Automated Fund Splitting:</b> Stripe Connect handles multi-party payouts (borrower → seller → referral commission → platform fees).</li>
          <li><b>Amortization Engine:</b> Exact principal & interest breakdown per installment with real-time running ledger updates.</li>
          <li><b>Role-Based Architecture:</b> 4 scoped portals for Sellers, Borrowers, Referrals, and Platform Admins.</li>
        </ul>
        <p>
          <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white" />
          <img src="https://img.shields.io/badge/Django_REST-092E20?style=flat-square&logo=django&logoColor=white" />
          <img src="https://img.shields.io/badge/Stripe_Connect-635BFF?style=flat-square&logo=stripe&logoColor=white" />
          <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
          <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" />
        </p>
        <p>
          🔗 <i><a href="https://mrsellernote.com" target="_blank">mrsellernote.com</a></i>
        </p>
      </td>
      <td width="45%" valign="top">
        <h3>⚡ Key Impact</h3>
        <br/>
        <p>
          💸 <b>Zero manual reconciliation:</b> 100% automated fund splitting<br/>
          🏦 <b>ACH & Card collection:</b> automated scheduled repayments<br/>
          🤝 <b>Multi-party commissions:</b> instant payout calculation
        </p>
      </td>
    </tr>

    <!-- Project 4: EasyBar -->
    <tr>
      <td width="55%" valign="top">
        <h3>🏗️ EasyBar — Rebar CAD & Manufacturing Platform</h3>
        <p>
          <b>End-to-end industrial platform</b> transforming manual rebar procurement into an automated digital workflow with real-time 2D drafting.
        </p>
        <ul>
          <li><b>Interactive 2D Drafting Engine:</b> Built with <code>Konva.js</code> for parametric sketching of bars, nets, and cages.</li>
          <li><b>Automated Vendor Quotations:</b> Instant machine-ready production tickets delivered directly to manufacturing partners.</li>
          <li><b>Industry Recognition:</b> Selected and accelerated in the prestigious Contech Incubator.</li>
        </ul>
        <p>
          <img src="https://img.shields.io/badge/React.js-20232a?style=flat-square&logo=react&logoColor=61DAFB" />
          <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" />
          <img src="https://img.shields.io/badge/Konva.js-0D83CD?style=flat-square" />
          <img src="https://img.shields.io/badge/AWS_Lambda_+_EC2-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" />
        </p>
        <p>
          🔗 <i><a href="https://easybar.co.il" target="_blank">easybar.co.il</a></i>
        </p>
      </td>
      <td width="45%" valign="top">
        <h3>⚡ Key Impact</h3>
        <br/>
        <p>
          💰 <b>$30M+</b> in potential orders in year 1<br/>
          👥 <b>1,000+ active users</b> in month 1<br/>
          ⚙️ <b>Automated machine-ready tickets</b> reducing production errors
        </p>
      </td>
    </tr>

    <!-- Project 5: Swerv Auto -->
    <tr>
      <td width="55%" valign="top">
        <h3>🚗 Swerv Auto — Dealership Market Intelligence & Sourcing</h3>
        <p>
          <b>Automotive SaaS platform</b> leveraging Open Car Data (OCD), automated lead scraping, and predictive market intelligence for vehicle acquisitions.
        </p>
        <ul>
          <li><b>Automated Data Pipeline:</b> AWS Lambda + Selenium workers for continuous data harvesting & synchronization.</li>
          <li><b>Sales Prospects Intelligence:</b> Smart algorithms analyzing vehicle market patterns to discover high-margin acquisition leads.</li>
        </ul>
        <p>
          <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white" />
          <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" />
          <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white" />
          <img src="https://img.shields.io/badge/AWS_Lambda_+_RDS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" />
        </p>
      </td>
      <td width="45%" valign="top">
        <h3>⚡ Key Impact</h3>
        <br/>
        <p>
          📈 <b>333% surge</b> in private-party acquisitions<br/>
          🚗 <b>47% increase</b> in customer showroom traffic<br/>
          💼 <b>12% boost</b> in dealership gross sales
        </p>
      </td>
    </tr>

    <!-- Project 6: Whisper Audio Transcript -->
    <tr>
      <td width="55%" valign="top">
        <h3>🎙️ Whisper Audio Transcript — Speech-to-Text AI Pipeline</h3>
        <p>
          <b>Open-source AI transcription pipeline</b> powered by OpenAI Whisper, delivering high-accuracy audio-to-text processing and transcription workflows.
        </p>
        <p>
          <img src="https://img.shields.io/badge/Python_3.11-14354C?style=flat-square&logo=python&logoColor=white" />
          <img src="https://img.shields.io/badge/OpenAI_Whisper-412991?style=flat-square&logo=openai&logoColor=white" />
          <img src="https://img.shields.io/badge/Speech--to--Text-009688?style=flat-square" />
        </p>
        <p>
          🔗 <i><a href="https://github.com/zain-hash-code/whisper-audio-transcript" target="_blank">github.com/zain-hash-code/whisper-audio-transcript</a></i>
        </p>
      </td>
      <td width="45%" valign="top">
        <h3>⚡ Key Capabilities</h3>
        <br/>
        <p>
          🎯 High-fidelity speech-to-text transcription<br/>
          ⚡ Support for multiple audio formats & multi-lingual speech<br/>
          🐳 Clean Python CLI & modular design
        </p>
      </td>
    </tr>
  </table>

</details>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- ═══════════════════════════════ ARSENAL ═══════════════════════════════ -->

<details open>
  <summary><h2>🧰 &nbsp;Technical Arsenal</h2></summary>

  <h3>🤖 &nbsp;AI / ML & LLM Engineering</h3>

  <p>
    <a href="#"><img alt="OpenAI" src="https://img.shields.io/badge/OpenAI-412991.svg?style=flat-square&logo=openai&logoColor=white"></a>
    <a href="#"><img alt="Anthropic" src="https://img.shields.io/badge/Anthropic_Claude-D97706.svg?style=flat-square&logo=anthropic&logoColor=white"></a>
    <a href="#"><img alt="Google Gemini" src="https://img.shields.io/badge/Google_Gemini-8E75C2.svg?style=flat-square&logo=google&logoColor=white"></a>
    <a href="#"><img alt="LangChain" src="https://img.shields.io/badge/LangChain-1C3C3C.svg?style=flat-square&logo=langchain&logoColor=white"></a>
    <a href="#"><img alt="LlamaIndex" src="https://img.shields.io/badge/LlamaIndex-6F42C1.svg?style=flat-square&logo=llama&logoColor=white"></a>
    <a href="#"><img alt="Hugging Face" src="https://img.shields.io/badge/Hugging_Face-FFD21E.svg?style=flat-square&logo=huggingface&logoColor=black"></a>
    <a href="#"><img alt="RAG" src="https://img.shields.io/badge/RAG_Pipelines-FF6F00.svg?style=flat-square&logo=databricks&logoColor=white"></a>
    <a href="#"><img alt="Whisper" src="https://img.shields.io/badge/OpenAI_Whisper-74aa9c.svg?style=flat-square&logo=openai&logoColor=white"></a>
    <a href="#"><img alt="sqlglot" src="https://img.shields.io/badge/sqlglot_(AST_Parsing)-2F80ED.svg?style=flat-square"></a>
  </p>

  <h3>🗃️ &nbsp;Vector Databases & Knowledge Stores</h3>

  <p>
    <a href="#"><img alt="pgvector" src="https://img.shields.io/badge/pgvector-4169E1.svg?style=flat-square&logo=postgresql&logoColor=white"></a>
    <a href="#"><img alt="Qdrant" src="https://img.shields.io/badge/Qdrant-DC382D.svg?style=flat-square&logo=qdrant&logoColor=white"></a>
    <a href="#"><img alt="Pinecone" src="https://img.shields.io/badge/Pinecone-000000.svg?style=flat-square&logo=pinecone&logoColor=white"></a>
    <a href="#"><img alt="ChromaDB" src="https://img.shields.io/badge/ChromaDB-FFB000.svg?style=flat-square&logo=chroma&logoColor=black"></a>
  </p>

  <h3>🔩 &nbsp;Backend & Web Frameworks</h3>

  <p>
    <a href="#"><img alt="Python" src="https://img.shields.io/badge/Python_3.11-14354C.svg?style=flat-square&logo=python&logoColor=white"></a>
    <a href="#"><img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688.svg?style=flat-square&logo=fastapi&logoColor=white"></a>
    <a href="#"><img alt="Django" src="https://img.shields.io/badge/Django-092E20.svg?style=flat-square&logo=django&logoColor=white"></a>
    <a href="#"><img alt="DRF" src="https://img.shields.io/badge/Django_REST-A30000.svg?style=flat-square&logo=django&logoColor=white"></a>
    <a href="#"><img alt="Celery" src="https://img.shields.io/badge/Celery-37814A.svg?style=flat-square&logo=celery&logoColor=white"></a>
    <a href="#"><img alt="SQLAlchemy" src="https://img.shields.io/badge/SQLAlchemy_2.0-D71F00.svg?style=flat-square&logo=sqlalchemy&logoColor=white"></a>
    <a href="#"><img alt="Pytest" src="https://img.shields.io/badge/Pytest-0A9EDC.svg?style=flat-square&logo=pytest&logoColor=white"></a>
    <a href="#"><img alt="Nginx" src="https://img.shields.io/badge/Nginx-009639.svg?style=flat-square&logo=nginx&logoColor=white"></a>
  </p>

  <h3>💻 &nbsp;Frontend & UI</h3>

  <p>
    <a href="#"><img alt="Next.js" src="https://img.shields.io/badge/Next.js_15-000000.svg?style=flat-square&logo=next.js&logoColor=white"></a>
    <a href="#"><img alt="React" src="https://img.shields.io/badge/React_19-20232a.svg?style=flat-square&logo=react&logoColor=%2361DAFB"></a>
    <a href="#"><img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6.svg?style=flat-square&logo=typescript&logoColor=white"></a>
    <a href="#"><img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat-square&logo=javascript&logoColor=black"></a>
    <a href="#"><img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4.svg?style=flat-square&logo=tailwindcss&logoColor=white"></a>
    <a href="#"><img alt="Konva" src="https://img.shields.io/badge/Konva.js_(2D_Canvas)-0D83CD.svg?style=flat-square"></a>
  </p>

  <h3>🗄️ &nbsp;Databases & Caching</h3>

  <p>
    <a href="#"><img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL_16-4169E1.svg?style=flat-square&logo=postgresql&logoColor=white"></a>
    <a href="#"><img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1.svg?style=flat-square&logo=mysql&logoColor=white"></a>
    <a href="#"><img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D.svg?style=flat-square&logo=redis&logoColor=white"></a>
    <a href="#"><img alt="SQLite" src="https://img.shields.io/badge/SQLite-003B57.svg?style=flat-square&logo=sqlite&logoColor=white"></a>
    <a href="#"><img alt="RabbitMQ" src="https://img.shields.io/badge/RabbitMQ-FF6600.svg?style=flat-square&logo=rabbitmq&logoColor=white"></a>
  </p>

  <h3>☁️ &nbsp;Cloud, DevOps & Automation</h3>

  <p>
    <a href="#"><img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E.svg?style=flat-square&logo=amazonwebservices&logoColor=white"></a>
    <a href="#"><img alt="EC2" src="https://img.shields.io/badge/EC2-FF9900.svg?style=flat-square&logo=amazonec2&logoColor=white"></a>
    <a href="#"><img alt="S3" src="https://img.shields.io/badge/S3-569A31.svg?style=flat-square&logo=amazons3&logoColor=white"></a>
    <a href="#"><img alt="RDS" src="https://img.shields.io/badge/RDS-527FFF.svg?style=flat-square&logo=amazonrds&logoColor=white"></a>
    <a href="#"><img alt="Lambda" src="https://img.shields.io/badge/Lambda-FF9900.svg?style=flat-square&logo=awslambda&logoColor=white"></a>
    <a href="#"><img alt="Textract" src="https://img.shields.io/badge/Textract-FF9900.svg?style=flat-square&logo=amazonwebservices&logoColor=white"></a>
    <a href="#"><img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED.svg?style=flat-square&logo=docker&logoColor=white"></a>
    <a href="#"><img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF.svg?style=flat-square&logo=github-actions&logoColor=white"></a>
    <a href="#"><img alt="Selenium" src="https://img.shields.io/badge/Selenium-43B02A.svg?style=flat-square&logo=selenium&logoColor=white"></a>
    <a href="#"><img alt="Stripe Connect" src="https://img.shields.io/badge/Stripe_Connect-635BFF.svg?style=flat-square&logo=stripe&logoColor=white"></a>
    <a href="#"><img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624.svg?style=flat-square&logo=linux&logoColor=black"></a>
  </p>

</details>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- ════════════════════════════ WHAT I BUILD ═══════════════════════════ -->

<details open>
  <summary><h2>🏗️ &nbsp;Core Competencies</h2></summary>

  <table>
    <tr>
      <td width="50%" valign="top">
        <h3 align="center">🤖 AI & Intelligent Systems</h3>
        <br/>
        <p align="center">
          <img src="https://img.shields.io/badge/-%E2%86%92_Conversational_Text--to--SQL_Engines-0D1117?style=flat-square" /><br/>
          <img src="https://img.shields.io/badge/-%E2%86%92_Document_AI_%26_OCR_Extraction_(Textract+Gemini)-0D1117?style=flat-square" /><br/>
          <img src="https://img.shields.io/badge/-%E2%86%92_Multi--Tenant_Vector_Search_(pgvector%2C_Qdrant)-0D1117?style=flat-square" /><br/>
          <img src="https://img.shields.io/badge/-%E2%86%92_Underwriting_%26_Credit_Memo_Synthesis-0D1117?style=flat-square" /><br/>
          <img src="https://img.shields.io/badge/-%E2%86%92_Audio_Transcription_Pipelines_(Whisper)-0D1117?style=flat-square" />
        </p>
      </td>
      <td width="50%" valign="top">
        <h3 align="center">⚙️ Core Software & Cloud</h3>
        <br/>
        <p align="center">
          <img src="https://img.shields.io/badge/-%E2%86%92_Multi--Party_Payment_Splitting_(Stripe_Connect)-0D1117?style=flat-square" /><br/>
          <img src="https://img.shields.io/badge/-%E2%86%92_Interactive_2D_CAD_%26_Canvas_Editors_(Konva)-0D1117?style=flat-square" /><br/>
          <img src="https://img.shields.io/badge/-%E2%86%92_Automated_Web_Scraping_%26_Sync_(Selenium+Lambda)-0D1117?style=flat-square" /><br/>
          <img src="https://img.shields.io/badge/-%E2%86%92_Secure_SSH_Bastion_Tunnels_%26_AST_Safety-0D1117?style=flat-square" /><br/>
          <img src="https://img.shields.io/badge/-%E2%86%92_Scalable_AWS_Deployments_%26_Docker_Pipelines-0D1117?style=flat-square" />
        </p>
      </td>
    </tr>
  </table>

</details>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- ══════════════════════════════ TROPHIES ══════════════════════════════ -->

<details open>
  <summary><h2>🏆 &nbsp;GitHub Trophies</h2></summary>

  <p align="center">
    <a href="https://github.com/ryo-ma/github-profile-trophy">
      <img src="https://github-profile-trophy.vercel.app/?username=zain-hash-code&theme=darkhub&no-frame=true&no-bg=true&column=7&margin-w=10&margin-h=10" alt="Trophies" width="100%" />
    </a>
  </p>

</details>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- ═══════════════════════════════ STATS ═══════════════════════════════ -->

<details open>
  <summary><h2>📊 &nbsp;The Numbers</h2></summary>

  <h3>🔥 &nbsp;Streak Stats</h3>

  <p align="center">
    <a href="https://github.com/DenverCoder1/github-readme-streak-stats">
      <img title="🔥 Keep the streak alive" alt="Zain's streak" src="https://github-readme-streak-stats.herokuapp.com/?user=zain-hash-code&theme=dark&hide_border=true&background=0D1117&ring=0CDA62&fire=FF6E40&currStreakLabel=0CDA62&sideLabels=C9D1D9&dates=8B949E&currStreakNum=C9D1D9&sideNums=C9D1D9&stroke=0CDA6233" width="70%"/>
    </a>
  </p>

  <h3>💻 &nbsp;GitHub Profile Stats</h3>

  <p align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats">
      <img alt="Zain's GitHub Stats" src="https://github-readme-stats.vercel.app/api/?username=zain-hash-code&show_icons=true&include_all_commits=true&count_private=true&theme=react&hide_border=true&bg_color=0D1117&title_color=0CDA62&icon_color=FF6E40&text_color=C9D1D9" height="195px"/>
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats">
      <img alt="Zain's Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=zain-hash-code&langs_count=8&layout=compact&theme=react&hide_border=true&bg_color=0D1117&title_color=0CDA62&icon_color=FF6E40&text_color=C9D1D9" height="195px"/>
    </a>
  </p>

  <p><b>Note:</b> Top languages is only a metric of the languages my public code consists of and doesn't reflect experience or skill level.</p>

  <br/>

  <h3>📈 &nbsp;Contribution Graph</h3>

  <p align="center">
    <a href="https://github.com/ashutosh00710/github-readme-activity-graph">
      <img alt="Zain's Activity Graph" src="https://github-readme-activity-graph.vercel.app/graph/?username=zain-hash-code&bg_color=0D1117&color=0CDA62&line=FF6E40&point=FFFFFF&area=true&area_color=0CDA6244&hide_border=true&custom_title=Contribution%20Graph" width="95%"/>
    </a>
  </p>

</details>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- ═══════════════════════ CURRENTLY VIBING WITH ════════════════════════ -->

<details>
  <summary><h2>🧪 &nbsp;Currently Experimenting With</h2></summary>
  <br/>

  <div align="center">
    <table>
      <tr>
        <td align="center" width="140">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" width="52" alt="Go"/>
          <br/><b>Go</b>
          <br/><sub>🟡 exploring</sub>
        </td>
        <td align="center" width="140">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" width="52" alt="Kubernetes"/>
          <br/><b>Kubernetes</b>
          <br/><sub>🟡 scaling</sub>
        </td>
        <td align="center" width="140">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg" width="52" alt="Terraform"/>
          <br/><b>Terraform</b>
          <br/><sub>🟡 tinkering</sub>
        </td>
        <td align="center" width="140">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/graphql/graphql-plain.svg" width="52" alt="GraphQL"/>
          <br/><b>GraphQL</b>
          <br/><sub>🟢 comfortable</sub>
        </td>
        <td align="center" width="140">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="52" alt="React"/>
          <br/><b>React 19</b>
          <br/><sub>🟢 production</sub>
        </td>
      </tr>
    </table>
  </div>

</details>

<!-- ═══════════════════════════ PHILOSOPHY ═══════════════════════════════ -->

<details>
  <summary><h2>💭 &nbsp;Engineering Philosophy</h2></summary>
  <br/>

  <div align="center">

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
  │   → Logs, metrics and evaluations are not optional              │
  │                                                                 │
  └─────────────────────────────────────────────────────────────────┘
  ```

  </div>

</details>

<!-- ══════════════════════════════ DEV QUOTE ══════════════════════════════ -->

<details>
  <summary><h2>💬 &nbsp;Random Dev Quote</h2></summary>
  <br/>

  <div align="center">
    <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" alt="Random Dev Quote" width="70%"/>
  </div>

</details>

<br/>

<!-- ═══════════════════════════════ FOOTER ═══════════════════════════════ -->

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<br/>

<p align="center">
  <a href="https://www.linkedin.com/in/zainulabiedeen/">
    <img src="https://img.shields.io/badge/-zainulabiedeen-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &#8287;
  <a href="mailto:zainulabideen78@outlook.com">
    <img src="https://img.shields.io/badge/-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  &#8287;
  <a href="https://github.com/zain-hash-code">
    <img src="https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&duration=3000&pause=2000&color=8B949E&center=true&vCenter=true&width=480&lines=Thanks+for+visiting!+%F0%9F%91%8B+Let's+build+something+intelligent+together." alt="Footer" />
</p>
