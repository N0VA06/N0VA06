<h1 align="center">Vijay Srinivas P</h1>

<p align="center">
  <b>AI Researcher · Research Engineer</b><br>
  B.Tech CSE (AI) @ Amrita Vishwa Vidyapeetham · Ex-Intern @ Schneider Electric<br><br>
  <a href="mailto:vijay.srinvas06@gmail.com">📧 vijay.srinvas06@gmail.com</a> ·
  <a href="https://www.linkedin.com/in/vijay-srinivas-9571942ab">LinkedIn</a> ·
  <a href="https://github.com/N0VA06">GitHub</a> ·
  <a href="https://medium.com/@vijay.srinvas06">Medium</a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=N0VA06&style=flat-square&color=blue" alt="Profile Views"/>
</p>

---

## About

I'm a third-year Computer Science (AI) student and researcher at Amrita Vishwa Vidyapeetham, Coimbatore. My research sits at the intersection of **transformer architecture design**, **neuroimaging ML**, and **biomedical computer vision** — building methods that work under the constraints of real biomedical data: high dimensionality, multi-site acquisition noise, and severe label scarcity.

I conduct research at the **Amrita Biomedical and Robotics Lab** and completed an industry R&D internship at **Schneider Electric**, where I deployed production-grade RAG systems on NVIDIA H100 infrastructure. I'm actively pursuing research internships and PhD opportunities at IITs, IISc, and international universities.

---

## Publications

### 🧠 ASD Classification from rs-fMRI via Riemannian Functional Connectivity
**IEEE APSCON 2026 · First Author · Best Paper Nominee**

Classification of Autism Spectrum Disorder from resting-state fMRI using the ABIDE dataset (867 subjects, 17 acquisition sites). Core contribution: mapping Pearson functional connectivity matrices onto a common Riemannian manifold via Tangent Space Embedding to achieve site-robust representations. Achieved **69.60% accuracy / 76.20% AUC-ROC**. Critically, we quantified the effect of data leakage on validation integrity — showing improper validation inflates accuracy by 22 percentage points (91.6% vs 69.7%), a methodological finding generalizable across biomedical imaging tasks.

> `fMRI · Graph Connectivity · Riemannian Geometry · Multi-site Harmonization · ASD · ABIDE`

---

### 📐 RotaryHybrid: Sparse-Dense Positional Embeddings for Transformers
**ACL Student Research Forum 2025 · First Author · Under Review**

Novel hybrid positional embedding architecture combining sparse learnable embeddings (with linear interpolation) and dense sinusoidal representations via a content-dependent importance gating mechanism. The RotaryHybrid variant applies RoPE in both the embedding space and attention layers for dual-level relative position encoding — achieving 70% parameter reduction over full learned embeddings while improving downstream task performance. Evaluated on IMDB, Yelp, Flickr8k, Yahoo Answers, and SQuAD.

> `Transformers · Positional Encoding · RoPE · NLP · Hybrid Architectures · Parameter Efficiency`

---

## Research Projects

---

### 🧬 fMRI-Guided BCI Electrode Placement (PANDA Dataset)
ML pipeline for predicting optimal cortical electrode placement for Brain-Computer Interfaces using the OpenNeuro ds005366 dataset (155 subjects, 7T fMRI, Motor2Class task). Extracts both structural features (FreeSurfer: cortical thickness, curvature, surface area) and task-based functional activation features from fMRIPrep outputs. Group-level analysis via nilearn to map whole-brain activation during motor vs. rest conditions — predicting subject-specific optimal electrode vertex given age, sex, and morphometric profile.

> `fMRI · BCI · fMRIPrep · FreeSurfer · nilearn · Task-Based Activation · Feature Engineering`

---

### 🔐 LLM Jailbreak Detection — Behavioral + Network Analysis
AI safety research combining behavioral timing features (HarmBench prompt sequences) with network-level IP analysis for jailbreak detection. FastAPI server-client architecture for real-time behavioral data collection. Fused behavioral fingerprints with session-level features for anomaly detection. 

> `LLM Security · AI Safety · HarmBench · Behavioral Analysis · FastAPI · Anomaly Detection`

---

### 🏭 Production RAG System — Schneider Electric (Industry)
Designed and deployed a GPU-accelerated retrieval-augmented generation system on NVIDIA H100 infrastructure handling 1,000+ daily queries at 95% accuracy. Vector database integration (Milvus, FAISS, Qdrant) with multi-stage retrieval, agentic reasoning chains, and CI/CD deployment on Azure.

> `RAG · LLM · Milvus · FAISS · Qdrant · Azure · FastAPI · Docker · NVIDIA H100`

---

## Technical Skills

| Domain | Tools & Methods |
|---|---|
| **Neuroimaging** | fMRIPrep · FreeSurfer · nilearn · nibabel · antspyx · SPM · MNI normalization · NeuroComBat |
| **Biomedical CV** | BraTS · cryo-ET/EM · 3D segmentation · GAT · GraphSAGE · SimpleITK |
| **NLP / Transformers** | BERT · RoPE · Hybrid embeddings · SQuAD QA · Sentiment analysis · HuggingFace |
| **ML / DL** | PyTorch · scikit-learn · XGBoost · AdamW · Label smoothing · Knowledge distillation |
| **MLOps / Infra** | FastAPI · Docker · Azure · AWS · CI/CD · Railway · Milvus · FAISS · Qdrant |
| **Languages** | Python · C++ · SQL · Bash · LaTeX |

---

## Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=N0VA06&show_icons=true&theme=default&hide_border=true&count_private=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=N0VA06&layout=compact&theme=default&hide_border=true" height="150"/>
</p>

---

## Recognitions

- 🥇 **Best Paper Nominee** — IEEE APSCON 2026
- 🏆 **4th Place** — AWS Blogathon 
- 🥈 **Top 10** — Agentic Ethereun Microsoft Hackathon  
- 🌐 **Top 160** — Google Cloud x MLB Hackathon

---

<p align="center">
  <i>Open to research collaborations in neuroimaging ML, transformer architecture, and biomedical computer vision.</i><br>
  <a href="mailto:vijay.srinvas06@gmail.com">vijay.srinvas06@gmail.com</a>
</p>





