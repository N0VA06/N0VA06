<h1 align="center">Vijay Srinivas P</h1>

<p align="center">
  <b>AI Researcher &nbsp;·&nbsp; Research Engineer &nbsp;·&nbsp; GenAI Builder</b><br><br>
  B.Tech CSE (AI) · Amrita Vishwa Vidyapeetham, Coimbatore &nbsp;|&nbsp<br>
  R&D GenAI Intern @ Schneider Electric &nbsp;·&nbsp; Undergrad Researcher 
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

-----

## About

I build at the boundary between **research and production** — designing novel architectures for neuroimaging and NLP problems, then shipping them as real deployed systems.

On the research side, my work spans **transformer architecture design** (positional embeddings, hybrid sparse-dense representations), **neuroimaging ML** (fMRI, BraTS, multi-site harmonization), and **biomedical computer vision**. On the engineering side, I architect and ship **production RAG systems**, **multi-agent LLM workflows**, and **MCP server integrations** — GenAI infrastructure built to handle real traffic.

-----

## 📄 Publications

### 🧠 ASD Classification from rs-fMRI via Riemannian Functional Connectivity

**IEEE APSCON 2026  ·  First Author  ·  Best Paper Nominee**

ASD classification from resting-state fMRI (ABIDE dataset, 867 subjects, 17 acquisition sites). Mapped Pearson functional connectivity matrices onto a Riemannian manifold via Tangent Space Embedding to produce site-robust representations — achieving **69.60% accuracy / 76.20% AUC-ROC**. Quantified the impact of data leakage, showing improper validation inflates accuracy by **22 percentage points** (91.6% vs 69.7%) — a methodological finding applicable across multi-site biomedical imaging.

`fMRI · Riemannian Geometry · Multi-site Harmonization · Graph Connectivity · ABIDE · ASD`

-----

### 📐 RotaryHybrid: Sparse-Dense Positional Embeddings for Transformers

**ACL Student Research Forum 2025  ·  First Author  ·  Accepted**

Hybrid positional embedding combining sparse learnable embeddings (with linear interpolation) and dense sinusoidal representations via a content-dependent importance gating mechanism. RotaryHybrid applies RoPE at both the embedding layer and attention layer for dual-level relative position encoding — achieving **70% parameter reduction** over full learned embeddings with improved downstream performance across text, image-caption, and QA benchmarks.

`Transformers · RoPE · Positional Encoding · Hybrid Architectures · NLP · Parameter Efficiency`

-----

## 🔬 Research Projects

### 🔬 HybridGATSAGE — Brain Tumor Segmentation on BraTS

Graph-hybrid segmentation architecture combining GAT and GraphSAGE for multi-modal MRI (T1, T1CE, T2, FLAIR). Full preprocessing pipeline: skull stripping → MNI normalization → spatial smoothing → NeuroComBat harmonization. Handles HGG/LGG class imbalance and multi-site acquisition noise across the BraTS2020 dataset.

`BraTS · GAT · GraphSAGE · nilearn · antspyx · NeuroComBat · MRI Segmentation`

-----

### 🧬 fMRI-Guided BCI Electrode Placement (PANDA Dataset)

ML pipeline for predicting optimal cortical electrode placement for Brain-Computer Interfaces using OpenNeuro ds005366 (155 subjects, 7T fMRI, Motor2Class task). Extracts structural features (FreeSurfer: cortical thickness, curvature, surface area) and task-based functional activation from fMRIPrep outputs. Whole-brain group-level nilearn analysis to identify the optimal cortical vertex per subject given age, sex, and morphometric profile.

`fMRI · BCI · fMRIPrep · FreeSurfer · nilearn · Motor Cortex · Feature Engineering`

-----

### 🔐 LLM Jailbreak Detection — Behavioral + Network Analysis

AI safety system combining behavioral timing features from HarmBench prompt sequences with network-level IP signals. FastAPI server-client architecture for real-time behavioral data collection. Fused session fingerprints with network features for jailbreak anomaly detection. Explored for publication at ACM CCS and CAMLIS 2026.

`LLM Security · AI Safety · HarmBench · Behavioral Analysis · FastAPI · Anomaly Detection`

-----

## ⚙️ Engineering Projects

### 🏭 R&D GenAI Intern — Schneider Electric

Designed and deployed a GPU-accelerated RAG system on NVIDIA H100 infrastructure handling **1,000+ daily queries at 95% accuracy**. Multi-stage retrieval with Qdrant + Azure + MongoDB. Achieved **90% latency reduction** through GPU-optimized inference, agentic reasoning chains, and CI/CD deployment on Azure.

`RAG · Qdrant · FAISS · Milvus · Azure · MongoDB · FastAPI · Docker · NVIDIA H100`

-----

### 🤖 Multi-Agent LLM Workflows with LangGraph

Hierarchical multi-agent systems using LangGraph — coordinating specialized sub-agents for research, analysis, and execution with structured state handoffs and tool calls. Built as Round 1 MVP at the OpenAI Buildathon.

`LangGraph · Multi-Agent · LLM Orchestration · Tool Use · OpenAI · Agentic AI`

-----

### 🔧 AI-Powered JIRA Manager + MCP Server Integration

Slack/Zoho Cliq–integrated JIRA bot with dual LLM backend (AWS Bedrock + Gemini). Natural language → structured JIRA issue creation with AI-extracted fields (type, priority, assignee, labels). MCP server layer enabling tool-calling AI agents to read and write project tasks programmatically. Deployed on Railway with FastAPI backend and React frontend.

`MCP · JIRA · FastAPI · React · AWS Bedrock · Gemini · Zoho Cliq · Railway`

-----

## 🛠️ Technical Skills

|Domain                |Stack                                                                        |
|----------------------|-----------------------------------------------------------------------------|
|**Neuroimaging**      |fMRIPrep · FreeSurfer · nilearn · nibabel · antspyx · NeuroComBat · SPM · MNI|
|**Biomedical CV**     |BraTS · cryo-ET/EM · GAT · GraphSAGE · SimpleITK · 3D Segmentation           |
|**NLP / Transformers**|BERT · RoPE · HuggingFace · SQuAD QA · Hybrid Embeddings · Fine-tuning       |
|**GenAI / Agents**    |LangChain · LangGraph · MCP Servers · RAG · Agentic Workflows · Tool Use     |
|**Vector DBs**        |Qdrant · Milvus · FAISS · Pinecone                                           |
|**ML / DL**           |PyTorch · scikit-learn · XGBoost · AdamW · Knowledge Distillation            |
|**MLOps / Infra**     |FastAPI · Docker · Azure · AWS · CI/CD · Railway · MongoDB                   |
|**Languages**         |Python · C++ · SQL · Bash · LaTeX                                            |

-----

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=N0VA06&show_icons=true&theme=default&hide_border=true&count_private=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=N0VA06&layout=compact&theme=default&hide_border=true" height="150"/>
</p>

-----

## 🏆 Recognitions

|                        |                                      |
|------------------------|--------------------------------------|
|🥇 **Best Paper Nominee**|IEEE APSCON 2026                      |
|🏗️ **Round 1 MVP**       |OpenAI Buildathon                     |
|🎯 **4th Place**         |AWS Blogathon                         |
|🚀 **Top 10**            |Agentic Ethereum · Microsoft Hackathon|
|🌐 **Top 160**           |Google Cloud × MLB Hackathon          |

-----

<p align="center">
  <i>Open to research collaborations and engineering roles in neuroimaging ML, GenAI systems, and transformer research.</i><br><br>
  <a href="mailto:vijay.srinvas06@gmail.com">vijay.srinvas06@gmail.com</a>
</p>