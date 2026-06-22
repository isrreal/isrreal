<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=32C9E1&size=28&center=true&vCenter=true&width=900&height=70&lines=Machine+Learning+Engineer+%26+Researcher;Applied+Math+%7C+MLOps+%7C+NLP;Computer+Science+%40+UFC+%E2%80%94+CNPq+RHAE" />
</div>

---

## About Me

I'm **Israel Souza**, a Computer Science undergrad at **UFC (Brazil)** and **ML Engineer & Researcher** under a **CNPq RHAE grant** at **Tieta.ai**.

I build systems where **mathematical rigor meets production engineering** — from deriving loss functions on paper to deploying containerized inference pipelines under CI/CD. My differentiator is depth: I understand *why* the math works and *how* to make it scale.

- 🧠 **Research:** Multitask learning, multimodal fusion, semantic retrieval
- ⚙️ **Engineering:** Async backends, MLOps pipelines, vector databases
- 📐 **Foundation:** Linear algebra, statistics, algorithm analysis (2 years as teaching assistant)

---

## Featured Projects

### 🎓 ENEM Question Analyzer — Multimodal MMoE Regressor
> *Multitask Learning · NLP · Production ML · CNPq RHAE Grant*

Predicts difficulty metrics of Brazil's national university exam questions by fusing **textual and semantic modalities** through a Multi-gate Mixture-of-Experts architecture. Built end-to-end: from bibliographic research to a Dockerized FastAPI serving layer.

- **Why it's hard:** Multitask regressors suffer from task interference — MMoE gates learn to route each task to specialized experts, reducing negative transfer
- **Stack:** PyTorch · HuggingFace · FAISS · FastAPI · Docker · GitLab CI/CD
- **Result:** 1-year R&D deliverable; outperformed hard-parameter sharing baselines on cross-task metrics

---

### 🕐 [Face Clock Evoluir — Facial Recognition Clock-In System](https://github.com/isrreal/face-clock-evoluir-public)
> *Computer Vision · Deep Learning · Backend Engineering · Proprietary*

A production SaaS for employee time tracking — no badge, no PIN, just your face. Combines **biometric verification**, **GPS geofencing**, and **AI-powered medical certificate classification** in a single async API.

- **Why it's hard:** Real-time face matching at scale requires unit-norm embeddings in ℝ⁵¹² and cosine similarity via dot product — not pixel comparison; geofencing uses Haversine on a sphere, not Euclidean distance
- **Stack:** InsightFace `buffalo_l` · pgvector · EfficientNet-B0 · pytesseract · FastAPI · PostgreSQL · Docker
- **Result:** Sub-second async face matching; hybrid CNN + OCR pipeline with traceable decision provenance

---

### 🦠 [End-to-End COVID-19 Forecasting System](https://github.com/isrreal/COVID-19-Forecasting-System)
> *ML Engineering · MLOps · Time Series*

Full MLOps pipeline for epidemic forecasting — experiment tracking, containerized serving, and REST API around an LSTM model. The point was never the model; it was everything around it.

- **Stack:** PyTorch · MLflow · Docker · FastAPI · PostgreSQL

---

### 🇧🇷 [Big Data Mining — Brazilian Emergency Aid](https://github.com/isrreal/AuxilioEmergencialQueries)
> *Data Engineering · High-Performance ETL*

Async ETL pipeline over **257 million** government records with aggressive SQL index optimization and interactive Streamlit dashboards.

- **Stack:** Python AsyncIO · Polars · PostgreSQL · Streamlit

---

### 📐 [Triple Roman Domination in Graphs — Undergraduate Thesis](https://github.com/isrreal/Triple-Roman-Domination-in-graphs)
> *Graph Theory · NP-Hard Optimization · Algorithms*

Metaheuristic solvers (Genetic Algorithms + Ant Colony Optimization) for the Triple Roman Domination problem — an NP-Hard combinatorial optimization challenge on graphs.

- **Stack:** C++ · Bash · Linux

---

## Tech Stack

| Domain | Tools |
|:---|:---|
| **Languages** | Python · C++ · Bash · LaTeX |
| **ML / DL** | PyTorch · HuggingFace · scikit-learn · FAISS · InsightFace |
| **MLOps** | MLflow · Docker · GitLab CI/CD |
| **Backend** | FastAPI · PostgreSQL · pgvector · AsyncIO · Alembic |
| **Systems** | Linux · Git · OpenCV |

---

## GitHub Stats

<div align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=isrreal&show_icons=true&count_private=true&hide_border=true&title_color=32C9E1&icon_color=32C9E1&text_color=FFF&bg_color=0d1117" />
  <img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=isrreal&layout=compact&hide_border=true&title_color=32C9E1&text_color=FFF&bg_color=0d1117"/>
</div>

---

## Contact

<div align="center">
  <a href="mailto:souzaferreira437@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  <a href="https://www.linkedin.com/in/israel-souza-84b8102b0" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</div>
