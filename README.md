<h1 align="center">Vijay Srinivas P</h1>

<p align="center">
  <b>AI Researcher &nbsp;·&nbsp; Research Engineer &nbsp;·&nbsp; GenAI Builder</b><br><br>
  B.Tech CSE (AI) · Amrita Vishwa Vidyapeetham, Coimbatore<br>
  R&amp;D GenAI Intern @ Schneider Electric &nbsp;·&nbsp; Undergrad Researcher
</p>

<p align="center">
  <a href="https://novaihq.tech">
    <img src="https://img.shields.io/badge/novaihq.tech-Visit_my_lab-00d9ff?style=for-the-badge&logo=safari&logoColor=white&labelColor=0a0a0a"/>
  </a>
</p>

<p align="center">
  <a href="mailto:vijay.srinvas06@gmail.com">
    <img src="https://img.shields.io/badge/Email-vijay.srinvas06@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/vijay-srinivas-9571942ab">
    <img src="https://img.shields.io/badge/LinkedIn-Vijay%20Srinivas-0077B5?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://github.com/N0VA06">
    <img src="https://img.shields.io/badge/GitHub-N0VA06-181717?style=flat-square&logo=github&logoColor=white"/>
  </a>
  <a href="https://medium.com/@vijay.srinvas06">
    <img src="https://img.shields.io/badge/Medium-@vijay.srinvas06-12100E?style=flat-square&logo=medium&logoColor=white"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=N0VA06&style=flat-square&color=blue" alt="Profile Views"/>
</p>

---

## 🌐 Currently building → [**novaihq.tech**](https://novaihq.tech)

> *novaihq is an applied AI research lab — the Operational Intelligence Engine: a reasoning layer for grids, data centers, and industrial infrastructure, grounded in published research and deployed systems.*

The site itself is a [full-stack React + Express project](https://github.com/N0VA06/websiteforstartup) — admin dashboard, self-hosted analytics, JWT auth, real-time visitor metrics. End-to-end shipped from research to production.

---

## About

I build at the boundary between **research and production** — designing novel architectures for neuroimaging and NLP problems, then shipping them as real deployed systems.

On the research side, my work spans **transformer architecture design** (positional embeddings, hybrid sparse-dense representations), **neuroimaging ML** (fMRI, BraTS, multi-site harmonization), and **biomedical computer vision**. On the engineering side, I architect and ship **production RAG systems**, **multi-agent LLM workflows**, and **MCP server integrations** — GenAI infrastructure built to handle real traffic.

---

## 📄 Publications

### 🧠 ASD Classification from rs-fMRI via Riemannian Functional Connectivity

**IEEE APSCON 2026 · First Author · Best Paper Nominee**

ASD classification from resting-state fMRI (ABIDE dataset, 867 subjects, 17 acquisition sites). Mapped Pearson functional connectivity matrices onto a Riemannian manifold via Tangent Space Embedding to produce site-robust representations — achieving **69.60% accuracy / 76.20% AUC-ROC**. Quantified the impact of data leakage, showing improper validation inflates accuracy by **22 percentage points** (91.6% vs 69.7%) — a methodological finding applicable across multi-site biomedical imaging.

`fMRI · Riemannian Geometry · Multi-site Harmonization · Graph Connectivity · ABIDE · ASD`

---

### 📐 RotaryHybrid: Sparse-Dense Positional Embeddings for Transformers

**ACL Student Research Forum 2025 · First Author · Under Review**

Hybrid positional embedding combining sparse learnable embeddings (with linear interpolation) and dense sinusoidal representations via a content-dependent importance gating mechanism. RotaryHybrid applies RoPE at both the embedding layer and attention layer for dual-level relative position encoding — achieving **70% parameter reduction** over full learned embeddings with improved downstream performance across text, image-caption, and QA benchmarks.

`Transformers · RoPE · Positional Encoding · Hybrid Architectures · NLP · Parameter Efficiency`

---

## 🔬 Research Projects

### 🧬 fMRI-Guided BCI Electrode Placement (PANDA Dataset)

ML pipeline for predicting optimal cortical electrode placement for Brain-Computer Interfaces using OpenNeuro ds005366 (155 subjects, 7T fMRI, Motor2Class task). Extracts structural features (FreeSurfer: cortical thickness, curvature, surface area) and task-based functional activation from fMRIPrep outputs. Whole-brain group-level nilearn analysis to identify the optimal cortical vertex per subject given age, sex, and morphometric profile.

`fMRI · BCI · fMRIPrep · FreeSurfer · nilearn · Motor Cortex · Feature Engineering`

---

### 🔐 LLM Jailbreak Detection — Behavioral + Network Analysis

AI safety system combining behavioral timing features from HarmBench prompt sequences with network-level IP signals. FastAPI server-client architecture for real-time behavioral data collection. Fused session fingerprints with network features for jailbreak anomaly detection. Explored for publication at ACM CCS and CAMLIS 2026.

`LLM Security · AI Safety · HarmBench · Behavioral Analysis · FastAPI · Anomaly Detection`

---

## ⚙️ Engineering Projects

### 🏭 R&D GenAI Intern — Schneider Electric

Designed and deployed a GPU-accelerated RAG system on NVIDIA H100 infrastructure handling **1,000+ daily queries at 95% accuracy**. Multi-stage retrieval with Qdrant + Azure + MongoDB. Achieved **90% latency reduction** through GPU-optimized inference, agentic reasoning chains, and CI/CD deployment on Azure.

`RAG · Qdrant · FAISS · Milvus · Azure · MongoDB · FastAPI · Docker · NVIDIA H100`

---

### 🤖 Multi-Agent LLM Workflows with LangGraph

Hierarchical multi-agent systems using LangGraph — coordinating specialized sub-agents for research, analysis, and execution with structured state handoffs and tool calls. Built as Round 1 MVP at the OpenAI Buildathon.

`LangGraph · Multi-Agent · LLM Orchestration · Tool Use · OpenAI · Agentic AI`

---

### 🔧 AI-Powered JIRA Manager + MCP Server Integration

Slack/Zoho Cliq–integrated JIRA bot with dual LLM backend (AWS Bedrock + Gemini). Natural language → structured JIRA issue creation with AI-extracted fields (type, priority, assignee, labels). MCP server layer enabling tool-calling AI agents to read and write project tasks programmatically. Deployed on Railway with FastAPI backend and React frontend.

`MCP · JIRA · FastAPI · React · AWS Bedrock · Gemini · Zoho Cliq · Railway`

---

### 🌐 [novaihq.tech](https://novaihq.tech) — Full-Stack Research-Lab Site

Personal research-lab website + admin platform. React 18 + Vite frontend, Express + JWT backend, self-hosted privacy-first analytics (event tracking, geo via geoip-lite, session fingerprinting, engagement metrics, Excel export). Deployed via GitHub Actions to GitHub Pages with custom domain; backend on Render. Mobile-responsive admin with real-time stats, milestone/achievement CRUD, and audit logging.

`React · TypeScript · Vite · Express · JWT · bcrypt · TailwindCSS · Framer Motion · Recharts`

---

## 🛠️ Technical Skills

| Domain | Stack |
|---|---|
| **Neuroimaging** | fMRIPrep · FreeSurfer · nilearn · nibabel · antspyx · NeuroComBat · SPM · MNI |
| **Biomedical CV** | BraTS · cryo-ET/EM · GAT · GraphSAGE · SimpleITK · 3D Segmentation |
| **NLP / Transformers** | BERT · RoPE · HuggingFace · SQuAD QA · Hybrid Embeddings · Fine-tuning |
| **GenAI / Agents** | LangChain · LangGraph · MCP Servers · RAG · Agentic Workflows · Tool Use |
| **Vector DBs** | Qdrant · Milvus · FAISS · Pinecone |
| **ML / DL** | PyTorch · scikit-learn · XGBoost · AdamW · Knowledge Distillation |
| **MLOps / Infra** | FastAPI · Docker · Azure · AWS · CI/CD · Railway · MongoDB |
| **Languages** | Python · C++ · TypeScript · SQL · Bash · LaTeX |

---

## 🏆 Recognitions

| | |
|---|---|
| 🥇 **Best Paper Nominee** | IEEE APSCON 2026 |
| 🏗️ **Round 1 MVP** | OpenAI Buildathon |
| 🎯 **4th Place** | AWS Blogathon |
| 🚀 **Top 10** | Agentic Ethereum · Microsoft Hackathon |
| 🌐 **Top 160** | Google Cloud × MLB Hackathon |

---

## 📊 GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=N0VA06&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub stats" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=N0VA06&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" height="170"/>
</p>

---

<p align="center">
  <i>Open to research collaborations and engineering roles in neuroimaging ML, GenAI systems, and transformer research.</i>
</p>

<p align="center">
  <a href="https://novaihq.tech">novaihq.tech</a> &nbsp;·&nbsp;
  <a href="mailto:vijay.srinvas06@gmail.com">vijay.srinvas06@gmail.com</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/vijay-srinivas-9571942ab">LinkedIn</a>
</p>
