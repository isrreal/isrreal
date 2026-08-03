<div align="center">
  <img
    src="https://readme-typing-svg.herokuapp.com?color=32C9E1&size=28&center=true&vCenter=true&width=950&height=100&lines=Neural+Network+Engineer+%26+Applied+ML+Researcher;Applied+Mathematics+%7C+Algorithms+%7C+Computational+Complexity;Neural+Network+Optimization+%7C+Computational+Performance+%7C+Multimodal+Learning;Applied+Machine+Learning+Research+%40+Tieta.ai"
    alt="Neural Network Engineer and Applied ML Researcher"
  />
</div>

---

## About Me

I'm **Israel Souza**, a Machine Learning Engineer and Applied ML Researcher from Brazil, currently working at **Tieta Artificial Intelligence**. My background is analytical and mathematically driven — I implement and optimize neural networks with a strong focus on computational performance.

I build Machine Learning systems involving neural network optimization, multimodal learning, representation learning and semantic retrieval, backed by production-oriented ML infrastructure.

I have completed the academic requirements for a **B.Sc. in Computer Science at the Federal University of Ceará — UFC**, with degree issuance pending. Before that, I spent two years as a teaching assistant for Algorithms, Calculus and Pre-Calculus, translating algorithmic complexity and mathematical foundations for undergraduate students.

My interests include **neural network optimization, computational performance, applied Machine Learning, computer vision and combinatorial optimization**.

What I care about most is **evaluation**: measuring before concluding, and distrusting my own results until an experiment survives a control group.

---

## Professional Experience

### R&D Researcher, AI for Proficiency Analysis — Tieta Artificial Intelligence

> *Educational Proficiency Analysis · Exam Performance Prediction · Psychometrics · Multimodal Learning*

I work on research and development of Artificial Intelligence for educational proficiency analysis and exam performance prediction, involving multimodal data, multitask architectures, representation learning and semantic retrieval.

My work includes:

* Modeling item characteristics with **Item Response Theory**, validating model-estimated signals against reference psychometric parameters
* Building **LLM inference pipelines orchestrated with DSPy**, including procedural dialogue generation and cognitive-trajectory tracking
* Comparing alternative approaches through **paired evaluation on identical items**, measuring both signal quality and inference cost per item
* Experimenting with **relative representations** and attention-based reducers in multitask regression architectures
* Developing reproducible PyTorch training and evaluation pipelines
* Conducting ablation studies and statistical hypothesis testing
* Building semantic-retrieval and vector-search systems
* Developing ML APIs, model-serving infrastructure and production-oriented workflows

From **April 2025 to July 2026**, I participated in an applied research project supported by the **CNPq RHAE program**. I continue working at Tieta Artificial Intelligence beyond the conclusion of the funded project.

> Internal datasets, architectures, results and implementation details are not publicly available due to confidentiality and intellectual-property restrictions.

### Teaching Assistant, Algorithms, Calculus and Pre-Calculus — Federal University of Ceará (UFC), Quixadá

> *Data Structures · Algorithms · Computational Complexity · Calculus*

I supported undergraduate students in data structures, algorithms, complexity analysis and Calculus, translating quantitative and algorithmic reasoning for students throughout their coursework — the mathematical foundation I now apply to neural network optimization.

**2022 to 2024.**

---

## Featured Case Study

### 🕐 [Face Clock Evoluir — Facial Recognition Attendance System](https://github.com/isrreal/face-clock-evoluir-public)

> *Computer Vision · Applied Machine Learning · Backend Engineering · Contracted System*

Sanitized public technical case study derived from a contracted attendance system built for an educational institution. The system is functional and in **final acceptance testing before deployment**.

It integrates facial recognition, vector similarity search, GPS-based geofencing and automated medical-document triage within a secure backend architecture.

* **Facial recognition:** 1:1 verification and 1:N identification using 512-dimensional embeddings
* **Vector retrieval:** Cosine similarity and KNN search with PostgreSQL and `pgvector`
* **Robustness:** Multi-frame aggregation, liveness validation and replay protection
* **Document processing:** EfficientNet-B0 combined with an OCR-based pipeline
* **Backend:** FastAPI, SQLAlchemy, Alembic, JWT revocation and Docker
* **Quality:** 142 automated tests and continuous integration

**Diagnostic work on the classification pipeline:**

* Traced a silent OCR failure to an **EXIF orientation tag** the imaging library ignored — documents reached the model sideways without raising any error
* Ruled out three candidate causes of underfitting through controlled experiments, including one of my own hypotheses that the measurement overturned
* Identified augmentation load as the real cause by ablation, **raising validation accuracy by thirteen percentage points**
* Re-ran the full evaluation afterwards, which **reversed an earlier conclusion** about how much the neural network contributed to the pipeline

> The public repository excludes proprietary production code, biometric data, client-specific configuration and identifiable information.

---

## Selected Research and Engineering Projects

### 📐 [Triple Roman Domination in Graphs](https://github.com/isrreal/Triple-Roman-Domination-in-graphs)

> *Graph Theory · Combinatorial Optimization · Metaheuristics*

Algorithms for the **Triple Roman Domination Problem**, an NP-complete combinatorial optimization problem defined over graphs.

* **Approaches:** Genetic Algorithm and MAX-MIN Ant System with RVNS
* **Exact baseline:** Integer Linear Programming
* **Evaluation:** Heuristic solutions compared with exact optimization results
* **Focus:** Graph theory, discrete optimization and algorithm design
* **Stack:** C++ · Bash · Linux · Integer Linear Programming

---

### 🇧🇷 [Brazilian Emergency Aid — Ingestion and Performance Experiments](https://github.com/isrreal/AuxilioEmergencialQueries)

> *Data Engineering · PostgreSQL · Reproducible Benchmarking*

Picked back up on my own initiative after being submitted as a university assignment, and rebuilt for real scale over a 31.6 GB Brazilian public dataset of approximately **257 million emergency-aid payment records**.

* **Ingestion:** Chunked Pandas transformation with asynchronous PostgreSQL binary `COPY` via `asyncpg`
* **Published baselines:** 100 thousand and 1 million rows, with per-stage timing and peak memory
* **Memory experiment:** Per-stage instrumentation across 100 thousand, 1 million and 5 million rows correlated retained-memory growth with the deduplication identifiers held in memory (**r = 0.99**, ≈107 MiB per million identifiers)
* **Reproducibility:** Alembic-managed schema, automated runner with an isolated database per run
* **Stack:** Python · Pandas · AsyncIO · PostgreSQL · Alembic · Docker Compose

> Staging-based deduplication, chunk-size comparison, Polars benchmarks and controlled index benchmarks with `EXPLAIN ANALYZE` remain part of the ongoing work.

---

## Tech Stack

| Domain                    | Technologies                                                               |
| :------------------------ | :--------------------------------------------------------------------------|
| **Machine Learning**      | PyTorch · scikit-learn · Optuna · InsightFace · DSPy                       |
| **Scientific Computing**  | NumPy · SciPy · Pandas · Matplotlib                                        |
| **Languages**             | Python · C++ · SQL · Bash · LaTeX                                          |
| **Data & Retrieval**      | PostgreSQL · pgvector · FAISS · SQLAlchemy                                 |
| **Backend & Infrastructure** | MLflow · Docker · FastAPI · GitHub Actions · GitLab CI/CD               |
| **Methods**               | Item Response Theory · Statistical Testing · Ablation Studies · Model Calibration · Time Series · Graph Optimization |

---

## Contact

<div align="center">
  <a href="mailto:souzaferreira437@gmail.com">
    <img
      src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"
      alt="Gmail"
    />
  </a>

  <a href="https://www.linkedin.com/in/israel-souza-84b8102b0" target="_blank">
    <img
      src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"
      alt="LinkedIn"
    />
  </a>

  <a href="https://isrreal.github.io/" target="_blank">
    <img
      src="https://img.shields.io/badge/Portfolio-0b1020?style=for-the-badge&logo=githubpages&logoColor=white"
      alt="Portfolio"
    />
  </a>
</div>
