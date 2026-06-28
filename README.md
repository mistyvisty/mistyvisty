# Hi, I'm Preeti Bhardwaj 👋


[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-mistyvisty.github.io-1F4E79?style=for-the-badge)](https://mistyvisty.github.io)
[![Medium](https://img.shields.io/badge/Medium-Read_my_writing-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@bhardwajpreeti357)
[![Email](https://img.shields.io/badge/Email-bhardwajpreeti357@gmail.com-D44638?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bhardwajpreeti357@gmail.com)

---

## About Me

🎓 currently learning and seeking roles in Data Science / GenAI / ML Engineering  
🔨 Built production-style systems from scratch — RAG, agents, fine-tuning, MLOps  

---

## 🛠️ Tech Stack

**GenAI & Agentic AI**

![LangChain](https://img.shields.io/badge/LangChain-000000?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-Multi--Agent-1C3C3C?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-Vector_Search-0066CC?style=flat-square)
![Pinecone](https://img.shields.io/badge/Pinecone-Vector_DB-00B388?style=flat-square)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Groq](https://img.shields.io/badge/Groq-LLaMA-F54F29?style=flat-square)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-Grounding_%26_Refusal-6A0DAD?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-Hybrid_Search_%26_Reranking-0052CC?style=flat-square)

**ML & Evaluation**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-Explainability-6A0DAD?style=flat-square)
![SMOTE](https://img.shields.io/badge/SMOTE-ImbalancedLearn-E76F51?style=flat-square)
![Optuna](https://img.shields.io/badge/Optuna-Hyperparameter_Tuning-4B8BBE?style=flat-square)

**Fine-Tuning & LLM Ops**

![QLoRA](https://img.shields.io/badge/QLoRA-PEFT_Fine--Tuning-8B5CF6?style=flat-square)
![PEFT](https://img.shields.io/badge/PEFT-LoRA_%26_Adapters-7C3AED?style=flat-square)
![Transformers](https://img.shields.io/badge/Transformers-HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![BitsAndBytes](https://img.shields.io/badge/BitsAndBytes-4bit_Quantisation-FF6B6B?style=flat-square)

**Deep Learning**

![CNN](https://img.shields.io/badge/CNN-Custom_Architecture-EE4C2C?style=flat-square)
![ResNet](https://img.shields.io/badge/ResNet--18-Transfer_Learning-EE4C2C?style=flat-square)
![GradCAM](https://img.shields.io/badge/Grad--CAM-Explainability-6A0DAD?style=flat-square)

**Production & MLOps**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Evidently](https://img.shields.io/badge/Evidently-Drift_Detection-1DB954?style=flat-square)
![Prometheus](https://img.shields.io/badge/Prometheus-Metrics-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-Dashboards-F46800?style=flat-square&logo=grafana&logoColor=white)

**Data & Business Intelligence**

![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Power_BI_Formulas-F2C811?style=flat-square)

---

## 🚀 Projects

### 🤖 GenAI & Agentic Systems

---

#### 🏥 Medical Research Assistant — Multi-Agent System
> `LangGraph` `Groq LLaMA 3.3-70B` `Streamlit` `Docker`

Three specialized agents working in sequence — Researcher → Summariser → Fact-Checker — on any medical topic. Hard-coded medical disclaimer; informational only. Containerized with Docker.

**Result: Sequential 3-agent pipeline with built-in claim validation**

🔗 [Repo](https://github.com/mistyvisty/medical-research-agent) · 🚀 [Live App](https://medical-research-agent-3mbhgune6spud5lszhhvqs.streamlit.app/)

---

#### 🎫 AI Support Triage Agent — Agentic Tool-Calling System
> `Groq LLaMA 3.3-70B` `Native Tool-Calling` `FAISS` `MiniLM` `Eval Harness`

Routes support tickets across three actions — draft, escalate, clarify — using native function-calling, not freeform text parsing. Hard-coded policy rules override model judgment for security/legal tickets. Built a labeled eval harness measuring routing accuracy separately from escalation recall.

**Result: 100% escalation recall on security/legal tickets · Overall routing accuracy 57.1% with documented diagnosis**

🔗 [Repo](https://github.com/mistyvisty/support-triage-agent)

---

#### 📊 AI CSV Analyst — Conversational Data Copilot
> `Groq LLaMA 3.3-70B` `Pandas` `Matplotlib` `Streamlit`

Natural language querying over raw CSVs with auto-rendered charts. Custom truncation algorithm handles datasets up to 200MB by preserving structural context within context-window limits.

🔗 [Repo](https://github.com/mistyvisty/ai_csv_analyst) · 🚀 [Live App](https://preeti-ai-csv-analyst.streamlit.app/)

---

### 🧠 RAG & LLM Fine-Tuning

---

#### 🩺 PCOS × Neurodivergence — Advanced RAG (Pinecone + Hybrid Search)
> `Pinecone` `BM25` `CrossEncoder` `LangChain` `Cohere Rerank` `MiniLM`

Upgraded RAG pipeline with Pinecone vector store, BM25 sparse retrieval, Reciprocal Rank Fusion hybrid search, and CrossEncoder re-ranking. A/B tested against FAISS baseline on 10 queries with documented retrieval quality improvement.

**Result: Hybrid search + reranking measurably outperforms dense-only retrieval**

🔗 [Repo](https://github.com/mistyvisty/pcos-neurodivergence-advanced-rag-pinecone)

---

#### 🧬 PCOS × Neurodivergence RAG Assistant
> `LangChain` `FAISS` `Groq LLaMA 3.1` `HuggingFace MiniLM`

RAG pipeline grounded in peer-reviewed clinical papers on PCOS and neurodivergence co-occurrence. Hallucination-aware system prompt forces refusal when context is insufficient; requires exact source citations on every answer.

**Result: Answers complex clinical questions with source citations, refuses when grounding is absent**

🔗 [Repo](https://github.com/mistyvisty/pcos-neurodivergence-rag) · 📝 [Medium](https://medium.com/@bhardwajpreeti357/i-built-an-ai-that-reads-clinical-research-papers-and-answers-questions-about-pcos-and-b1f526784409)

---

#### 🤖 Fine-Tuned Phi-3 on PCOS Data — QLoRA
> `QLoRA` `PEFT` `Transformers` `BitsAndBytes` `Google Colab`

Fine-tuned Phi-3-mini with 4-bit quantisation and LoRA (rank=8, alpha=16) on a PCOS QA instruction dataset derived from RAG chunks. Compared base vs fine-tuned responses on 5 clinical questions.

🔗 [Repo](https://github.com/mistyvisty/pcos-finetune-phi3-lora)

---

### ⚙️ ML Engineering & MLOps

---

#### 🏥 Hospital Readmission Risk Predictor + ML Monitoring
> `XGBoost` `FastAPI` `Evidently` `Prometheus` `Grafana` `Docker` `GitHub Actions`

Production ML pipeline on 101,766 patient records with live monitoring layer. Removed target-leaking features, SMOTE inside ImbPipeline, FastAPI serving with Pydantic schemas, Evidently drift detection, Prometheus metrics, Grafana dashboards, Docker Compose, and CI/CD.

**Result: Mean CV AUC 0.581 — reported honestly, consistent with published benchmarks for this genuinely hard problem**

🔗 [Repo](https://github.com/mistyvisty/hospital-readmission-predictor) · 🚀 [Live App](https://hospital-readmission-bz7hqjeye7fgsppfs3pwqm.streamlit.app/)

---

#### 🛡️ Healthcare Insurance Fraud Detection Dashboard
> `PostgreSQL` `Docker` `Streamlit` `Plotly`

Full-stack fraud detection on 10,000 insurance claims using SQL window functions and CTEs, containerized with Docker Compose. Interactive dashboard surfaces fraud by provider, insurance type, state, and chronic condition.

**Result: 829 fraud cases (8.29%) · $972,902 fraud gap identified on $5,728,044 total claimed**

🔗 [Repo](https://github.com/mistyvisty/insurance-fraud) · 🚀 [Live App](https://insurance-fraud-d5ex7mayryye9gjonynmbg.streamlit.app/)

---

### 🖼️ Deep Learning & Computer Vision

---

#### 🛒 Amazon Catalog Quality Gate — CNN + Transfer Learning
> `PyTorch` `ResNet-18` `Grad-CAM` `Google Colab T4`

Automated image validation pipeline classifying e-commerce product photos as High / Low quality. Built a custom 3-layer CNN from scratch, then upgraded to ResNet-18 transfer learning. Grad-CAM heatmaps confirm the model attends to fabric texture on high-quality images — not shortcuts.

**Result: CNN 99.1% · ResNet-18 99.9% · Grad-CAM validates learned features**

🔗 [Repo](https://github.com/mistyvisty/amazon-catalog-quality-gate)

---

### 📊 Data Science & Machine Learning

---

#### 🩺 PCOS Detection & Risk Prediction
> `Random Forest` `XGBoost` `SHAP` `SMOTE` `ImbPipeline` `5-Fold Stratified CV`

ML pipeline on 541 records from 10 hospitals. Engineered `Total_follicles` feature — became the #1 SHAP predictor. Zero data leakage across 5-fold stratified CV. Threshold tuned for recall > 90% because false negatives are clinically worse than false positives.

**Result: Random Forest Mean AUC 0.973 · Recall 91.4% at tuned threshold**

🔗 [Repo](https://github.com/mistyvisty/PCOS_Detection_Medical)

---

#### 🏦 Bank Customer Churn Prediction
> `XGBoost` `SHAP Beeswarm` `ImbPipeline` `5-Fold CV`

Caught a target-leaking feature (`Complain` — 0.996 correlation with churn, only knowable after the customer already churned). Removed it. SHAP Beeswarm surfaces Age and NumOfProducts as real predictors. Identified Germany as highest-risk market.

**Result: XGBoost ROC-AUC 0.847 · Recommended Germany-specific retention strategy**

🔗 [Repo](https://github.com/mistyvisty/Bank-Churn-Prediction)

---

### 📈 SQL & Business Intelligence

---

#### 🛒 Superstore Sales Analysis — SQL + Power BI
> `SQL` `SQLite` `Power BI` `DAX` `Python`

12 SQL queries — aggregations, CTEs, window functions, discount impact analysis — on 4 years of retail transaction data. Interactive Power BI dashboard with regional map, category breakdown, and DAX measures.

**Result: Identified $125K in losses from aggressive discounting in specific sub-categories**

🔗 [Repo](https://github.com/mistyvisty/Superstore_SQL_and_Power_BI)

---

## 📝 Latest Writing

- [Why I Built a PCOS Prediction Model — And Why It Was Never Just a Portfolio Project](https://medium.com/@bhardwajpreeti357/why-i-built-a-pcos-prediction-model-and-why-it-was-never-just-a-portfolio-project-85f64126ed2f)
- [I Built an AI That Reads Clinical Research Papers and Answers Questions About PCOS and Neurodivergence](https://medium.com/@bhardwajpreeti357/i-built-an-ai-that-reads-clinical-research-papers-and-answers-questions-about-pcos-and-b1f526784409)

---

## 📚 Currently Studying

- 📖 [Notion Live Notes](https://spiral-game-e5b.notion.site/ML-Interview-Prep-Live-Reading-Notes-566ee8267299463b90dbe8c04434e496) — Chip Huyen's ML Interviews Book + Grokking ML


---

*Open to Data Scientist · GenAI Engineer · ML Engineer roles*
