<!-- ✨ HEADER ✨ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=230&section=header&text=Raghav%20S&fontSize=70&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=AI%20Systems%20%E2%80%A2%20Backend%20for%20AI%20%E2%80%A2%20LLM%20Reliability&descSize=20&descAlignY=60" alt="Raghav S banner" width="100%"/>

<a href="https://github.com/raghav-404">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=700&lines=Hi+%F0%9F%91%8B+I'm+Raghav;CS+Student+%40+VIT+Chennai+%F0%9F%8E%93;Building+RAG+apps+and+agent+workflows+%F0%9F%A4%96;Obsessed+with+reliable%2C+testable+LLM+systems+%F0%9F%9B%A1%EF%B8%8F;Open+to+AI%2FBackend+internships+%F0%9F%9A%80" alt="Typing animation" />
</a>

<br/>

</div>

---

## 👋 About Me

I'm **Raghav** 🎓. I like building AI applications where I can understand every moving part: how retrieval ranks results, how an agent decides, and how a system behaves when something goes wrong.

- 🔍 I enjoy building **RAG applications** and **agent workflows** with readable, modular code
- 🧱 I care about **structured outputs**, **explicit failure handling**, and **meaningful tests**
- 🧪 I'm interested in **LLM reliability, evaluation, and observability**
- 🌱 Currently learning by building, breaking, testing, and rebuilding
- 💼 **Open to AI / backend internships** and **open-source collaboration**

---

## 🎯 Career Interests

| 🧠 AI Systems Engineering | ⚙️ Backend for AI | 🛡️ LLM Reliability | 📊 Evaluation & Observability |
|:---:|:---:|:---:|:---:|
| Retrieval and agent workflows | APIs, validation, persistence | Safety checks, failure handling | Tracing, evals, debugging |

---

## 🛠️ Tech Stack

### 🐍 Languages & Backend
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" alt="Pydantic"/>
</p>

### 🧠 AI & Retrieval
<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/LangGraph-2E7D6B?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge" alt="Groq"/>
  <img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white" alt="FAISS"/>
  <img src="https://img.shields.io/badge/BM25-FF8C00?style=for-the-badge" alt="BM25"/>
</p>

### 🗄️ Databases
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/>
</p>

### 🔧 Reliability & Tools
<p>
  <img src="https://img.shields.io/badge/LangSmith-F59E0B?style=for-the-badge&logo=langchain&logoColor=white" alt="LangSmith"/>
  <img src="https://img.shields.io/badge/Promptfoo-7C3AED?style=for-the-badge" alt="Promptfoo"/>
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="pytest"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
</p>

---

## 🚀 Featured Projects

| Project | What it does | Stack | Link |
|:--|:--|:--|:--:|
| 🛡️ **LLM Reliability Platform** | Ingests LLM traces, redacts sensitive data, and evaluates responses with a structured Groq judge | Python, FastAPI, Pydantic, SQLite, Groq, LangSmith, Promptfoo, Docker | [🔗 Repo](https://github.com/raghav-404/llm-reliability-platform) |
| 📚 **Hybrid RAG Retrieval Engine** | Document QA that fuses FAISS and BM25 rankings, with citations and timings | Python, LangChain, FAISS, BM25, Groq, FastAPI, Sentence Transformers | [🔗 Repo](https://github.com/raghav-404/rag-retrieval-engine) |
| 🤖 **Multi-Agent Financial Debate** | LangGraph bull / bear / judge / critic workflow with validated decisions | Python, LangGraph, Groq, FastAPI, Pydantic, PostgreSQL | [🔗 Repo](https://github.com/raghav-404/multi-agent-debate) |

### 🛡️ LLM Reliability Platform
> *Trace, sanitize, and evaluate LLM application outputs.*

- 📥 Receives completed LLM application traces through a **FastAPI** service
- 🔒 Validates inputs and detects/redacts common sensitive-data patterns
- 🗃️ Stores sanitized traces in **SQLite**
- ⚖️ Evaluates responses using a structured **Groq** judge request
- 🔭 Optionally exports sanitized traces and evaluation feedback to **LangSmith**
- ✅ Includes **pytest** tests, **Promptfoo** safety checks, and **Docker** support

**Stack:** `Python` `FastAPI` `Pydantic` `SQLite` `Groq` `LangSmith` `Promptfoo` `Docker`

### 📚 Hybrid RAG Retrieval Engine
> *Two retrievers, one fused ranking, answers you can trace back to sources.*

- 🔎 Document question-answering with independent **FAISS** and **BM25** retrieval
- 🧮 Combines rankings using **reciprocal rank fusion**
- 🪄 Supports optional **reranking** and **query rewriting**
- 📎 Returns answers with **chunk citations**, **timings**, and **request IDs**
- 📊 Includes retrieval evaluation, mocked tests, and **GitHub Actions**

**Stack:** `Python` `LangChain` `FAISS` `BM25` `Groq` `FastAPI` `Sentence Transformers`

### 🤖 Multi-Agent Financial Debate
> *A decision-support demonstration of structured multi-agent reasoning.*

- 🕸️ Uses **LangGraph** to coordinate bull, bear, judge, and conditional critic roles
- 🧠 All roles use one configured **Groq** model
- 🧾 Validates structured decisions with **Pydantic**
- 💻 Provides **CLI** and **FastAPI** interfaces, with optional **PostgreSQL** persistence
- 🧪 Includes a baseline-versus-debate evaluation harness, mocked tests, and **GitHub Actions**

**Stack:** `Python` `LangGraph` `Groq` `FastAPI` `Pydantic` `PostgreSQL`

---

## 🤝 Verified Open-Source Contributions

Two merged documentation PRs to [**langchain-ai/docs**](https://github.com/langchain-ai/docs):

| PR | Contribution | Status |
|:--:|:--|:--:|
| [#4035](https://github.com/langchain-ai/docs/pull/4035) | 📖 Clarified LangGraph **recursion-limit** behavior | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=github&logoColor=white) |
| [#4036](https://github.com/langchain-ai/docs/pull/4036) | 🧰 Clarified **unsupported LangGraph JavaScript build flags** | ![Merged](https://img.shields.io/badge/Merged-8957E5?style=flat-square&logo=github&logoColor=white) |

---

## 🌱 Engineering Interests

- 📊 Better **evaluation datasets** and **retrieval comparisons**
- 🔌 **Reliable APIs** and **validated agent outputs**
- 🔭 **Tracing and debugging** AI workflows
- ⚖️ Understanding the **limitations of LLM-as-judge** evaluation

---

## 📈 GitHub Stats

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=raghav-404&show_icons=true&theme=tokyonight&hide_border=true&count_private=false" alt="Raghav's GitHub stats"/>
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=raghav-404&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages"/>

<br/>

<img src="https://streak-stats.demolab.com/?user=raghav-404&theme=tokyonight&hide_border=true" alt="GitHub streak"/>

</div>

---

## 📬 Let's Connect

I'm looking for **AI / backend internship** opportunities and happy to collaborate on **open-source** work. If you're building something around RAG, agents, or LLM evaluation, say hi! 👋

<div align="center">

<a href="https://www.linkedin.com/in/raghav404/"><img src="https://img.shields.io/badge/LinkedIn-Let's%20Talk-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://github.com/raghav-404"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="Follow on GitHub"/></a>

<br/><br/>

<i>⭐ Thanks for stopping by. Build things, test them, and understand them. ⭐</i>

</div>

<!-- ✨ FOOTER ✨ -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=160&section=footer&text=Raghav%20S&fontSize=36&fontColor=ffffff&fontAlignY=65&animation=twinkling" alt="Footer" width="100%"/>
