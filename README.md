# Pavle Savković

Data Scientist and Applied ML Engineer with an MSc in Computational Social Systems from TU Graz.

I build end-to-end ML systems, from raw data to evaluated results, mostly in NLP and computer vision. I care about measuring things properly: every project below has its own evaluation against ground truth, including where it falls short.

Before data science I played professional football in Montenegro, which is where my computer vision project comes from.

## Featured projects

### Ask Parliament
[github.com/pavlesav/ask-parliament](https://github.com/pavlesav/ask-parliament)

Cross-lingual question answering over 3.4 million speeches from 29 European parliaments (ParlaMint 5.0, 1996-2024). Answers come back in English with citations to the original speeches, which are retrieved in their own language.

- BGE-m3 embeddings in Qdrant, query expansion (paraphrases + HyDE), reciprocal-rank fusion, cross-encoder reranking and a corrective retrieval round, then grounded generation with the Claude API
- FastAPI backend, Streamlit frontend, Docker Compose; no LangChain or LlamaIndex, every stage written directly against the model and database APIs
- On a 100-topic golden set, reranking lifts precision@10 from 0.69 to 0.79; LLM-judged answers score 4.6/5 for groundedness, and all 22 out-of-corpus questions were declined

### Football Computer Vision
[github.com/pavlesav/football-computer-vision](https://github.com/pavlesav/football-computer-vision)

Turns full-match broadcast video from Montenegro's first league, which no commercial data provider covers, into match event data: passes, carries, possession, goals and which player made them.

- Fine-tuned YOLOv8 detection (mAP50 0.94 on held-out matches) with BoT-SORT tracking, PnLCalib camera calibration, and a pitch-space Kalman filter for the ball
- Rule-based event detection exported in StatsBomb format; goals read from the broadcast scoreboard with OCR
- Players identified by reading shirt numbers with a vision-language model (Qwen2-VL) and linking track fragments with OSNet re-identification
- Across 7 full matches, possession is within 4 percentage points of SofaScore and the final score matched on all 7

### Parliamentary debates NLP pipeline (MSc thesis)
[github.com/pavlesav/master-thesis](https://github.com/pavlesav/master-thesis)

Context-aware topic labelling and linguistic style analysis over 1.4 million parliamentary speeches from Austria, Croatia and Great Britain.

- Sittings segmented into agenda episodes, embedded with BGE-m3, clustered (UMAP + GMM) and mapped to Comparative Agendas Project policy domains with an LLM
- Linguistic style profiled with LIWC-22 by topic, party role, gender, age and over time
- A journal article based on the thesis is under review at the Journal of Computational Social Science

## Other work

- [Time Series Anomaly Detection](https://github.com/pavlesav/Time-Series-Anomaly-Detection)
- [Predicting markets from merger announcement speeches](https://github.com/pavlesav/Predicting-Markets-using-Merger-Announcement-Speeches)
- [Euro 2024 visualizations](https://github.com/pavlesav/Euro-2024-visualizations) (Streamlit app)

## Tech

**Languages:** Python, SQL, R, LaTeX  
**ML and NLP:** PyTorch, scikit-learn, Hugging Face Transformers, sentence embeddings, BERTopic, spaCy, NLTK  
**Computer vision:** Ultralytics YOLO, OpenCV, re-identification models, camera calibration  
**LLMs and retrieval:** Claude API, OpenAI API, Qdrant, cross-encoder reranking, LLM-as-judge evaluation  
**Data and apps:** pandas, NumPy, matplotlib, FastAPI, Streamlit, Docker  
**Networks and simulation:** NetworkX, Mesa

## Teaching

Teaching Assistant at TU Graz for Master's courses with 100+ students: practical Python sessions and project grading.

- [Computational Modelling of Social Systems 2025](https://github.com/pavlesav/ComputationalModellingSocialSystems2025)
- [Computational Modelling of Social Systems 2024](https://github.com/pjercic/ComputationalModellingSocialSystems2024)
- [Foundations of Computational Social Systems 2024](https://github.com/pjercic/FoundationsOfCSS2024)
- Network Science 2025

## Contact

pavleav@gmail.com · [LinkedIn](https://www.linkedin.com/in/pavle-savkovic/)
