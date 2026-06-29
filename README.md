# 👋 Hi, I'm Pavle Savković

I’m a **Data Scientist / Applied ML Engineer** with an MSc in **Computational Social Systems (TU Graz)**.  
I build end-to-end pipelines that turn raw data into **models, evaluation, and clear insights**, especially in **NLP/Text Analytics** and **Computer Vision**.

⚽ Former professional football player, I like projects that are practical, performance-driven, and easy to demo.

---

## 🔎 What I’m focused on
- **NLP / Text Analytics:** topic modeling, embeddings, clustering, labeling & evaluation, linguistic style profiling  
- **Applied ML / Prototyping:** computer vision pipelines, tracking-by-detection, turning video into structured data  
- **Data Work:** Python + SQL, analysis, visualization, reproducible notebooks and workflows

---

## 🧰 Tech & Tools
**Languages:** Python, R, SQL, LaTeX  
**ML/NLP:** scikit-learn, PyTorch, spaCy, NLTK, BERTopic  
**Data:** pandas, NumPy, matplotlib, seaborn  
**Networks / Simulation:** NetworkX, Mesa  
**Workflow:** Git, Jupyter, Colab

---

## 🚀 Featured projects

### 1) 🏛️ Parliamentary NLP pipeline (MSc thesis)
**Repo:** https://github.com/pavlesav/master-thesis  
**Goal:** analyze large-scale parliamentary debates with context-aware topic modeling and linguistic style features.  
**Approach:** debate segmentation → embeddings → clustering/topic modeling → topic labeling → LIWC-22 style profiling → temporal analysis.  
**Status:** MSc thesis. **Manuscript in preparation** based on the same work.

**Quick start:** the repository README contains setup + how to reproduce the main results.

---

### 2) 🤖 Ask Parliament (production-shaped RAG)
**Repo:** https://github.com/pavlesav/ask-parliament  
**Goal:** ask natural-language questions over the full **ParlaMint 5.0** corpus — 3.4M speeches across 29 European parliaments (1996–2024) — and get grounded, cited answers.  
**Approach:** Qdrant index over BGE-m3 embeddings → **agentic retrieval** (multi-query + HyDE → RRF fusion → cross-encoder reranking → self-correcting CRAG loop) → grounded, cited generation via the **Claude API**. **Cross-lingual** — ask in English, retrieve speeches in their original language. Shipped as a **FastAPI backend + thin Streamlit UI + Qdrant** via Docker Compose, with retrieval and LLM-as-judge generation evals. **No LangChain/LlamaIndex** — every stage written explicitly.  
**Status:** end-to-end and runnable on the full 29-parliament corpus (extends the ParlaMint data from the thesis above).

---

### 3) ⚽ Football computer vision (detection + tracking pipeline)
**Repo:** https://github.com/pavlesav/football-computer-vision  
**Goal:** turn match footage into structured data for downstream analytics and visual outputs.  
**Approach:** YOLO-based detection + tracking-by-detection pipeline (built on my own dataset).

---

### 4) 📊 Euro 2024 visualizations (Streamlit app)
**Repo:** https://github.com/pavlesav/Euro-2024-visualizations  
**Goal:** interactive match analytics and football graphics.  
**Approach:** data cleaning + feature building + plotting + app interface (Streamlit).  
Includes a deployed app link in the repo.

---

## 📌 Other work (selected)
- ⏱️ **Time Series Anomaly Detection:** https://github.com/pavlesav/Time-Series-Anomaly-Detection  
- 📈 **Predicting markets from merger announcement speeches:**  
  https://github.com/pavlesav/Predicting-Markets-using-Merger-Announcement-Speeches

---

## 👨‍🏫 Teaching (TU Graz)
I’ve been a **Teaching Assistant** for Master’s level courses (100+ students), running practical Python sessions and grading projects.

### Teaching repositories
- **Computational Modelling of Social Systems 2024:** https://github.com/pjercic/ComputationalModellingSocialSystems2024  
- **Foundations of Computational Social Systems 2024:** https://github.com/pjercic/FoundationsOfCSS2024  
- **Computational Modelling of Social Systems 2025:** https://github.com/pavlesav/ComputationalModellingSocialSystems2025  
- **Network Science 2025** 
---

## 📫 Connect
- 📧 Email: pavleav@gmail.com  
- 💼 LinkedIn: https://www.linkedin.com/in/pavle-savkovic-907b0324a/  
- 🐙 GitHub: https://github.com/pavlesav
