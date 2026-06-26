# Hi, I'm Preeti Bhardwaj 👋

### Data Scientist · GenAI & Agentic Systems · RAG & LLM Engineering

*I build AI systems that know when to answer, when to refuse, and when to ask for help.*

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-mistyvisty.github.io-1F4E79?style=for-the-badge)](https://mistyvisty.github.io)
[![Medium](https://img.shields.io/badge/Medium-Read_my_writing-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@bhardwajpreeti357)
[![Email](https://img.shields.io/badge/Email-bhardwajpreeti357@gmail.com-D44638?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bhardwajpreeti357@gmail.com)

---

## About me

I build production-style ML and GenAI systems — end-to-end pipelines with real engineering decisions baked in.

My work has a consistent thread: **responsible AI**. Every system I build has an explicit answer to "what happens when the model is wrong?" — whether that's a SMOTE pipeline that can't leak into validation folds, a RAG assistant that refuses to answer when context is missing, or an agentic triage system that hard-codes escalation rules for high-stakes decisions instead of leaving them to probabilistic judgment.

I'm actively looking for roles in **Data Science / GenAI / ML Engineering**.

---

## 🛠️ Tech Stack

**GenAI & Agentic AI**

![LangChain](https://img.shields.io/badge/LangChain-000000?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-Multi--Agent-1C3C3C?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-Vector_Search-0066CC?style=flat-square)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Groq](https://img.shields.io/badge/Groq-LLaMA-F54F29?style=flat-square)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-Grounding_%26_Refusal-6A0DAD?style=flat-square)

**ML & Evaluation**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-Explainability-6A0DAD?style=flat-square)
![SMOTE](https://img.shields.io/badge/SMOTE-ImbalancedLearn-E76F51?style=flat-square)

**Production & Deployment**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Data & Visualization**

![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

---

## 🚀 Projects

### 🏥 Medical Research Assistant — Multi-Agent System
> `Python` `LangGraph` `Groq LLaMA 3.3-70B` `Streamlit` `Docker`

A multi-agent AI system that researches any medical topic using three specialized agents working in sequence: a Researcher agent gathers comprehensive medical information, a Summariser agent converts it into patient-friendly language, and a Fact-Checker agent validates claims and flags anything uncertain. Containerized with Docker and shipped with a clear medical disclaimer — informational only, not a substitute for a doctor.

**Result: Sequential 3-agent pipeline (Research → Summarise → Fact-Check) with built-in claim validation**

🔗 [Repo](https://github.com/mistyvisty/medical-research-agent) · 🚀 [Live App](https://medical-research-agent-3mbhgune6spud5lszhhvqs.streamlit.app/)

---

### 🛡️ Insurance Fraud Detection
> `Python` `Streamlit`

A fraud detection app deployed for live use.

**🔗 [Live App](https://insurance-fraud-d5ex7mayryye9gjonynmbg.streamlit.app/)**

---

### 🎫 AI Support Triage Agent — Agentic Tool-Calling System
> `Python` `Groq LLaMA 3.3-70B` `Native Tool-Calling` `FAISS` `MiniLM` `Eval Harness`

An agent that routes support tickets across three actions — draft, escalate, or clarify — using native function-calling, not freeform text parsing. Hard-coded policy rules override model judgment for security/legal tickets. Built a labeled eval harness measuring routing accuracy separately from hard-trigger escalation recall.

**Result: 100% escalation recall on security/legal tickets · Overall routing accuracy 57.1% with documented diagnosis and fix**

🔗 [Repo](https://github.com/mistyvisty/support-triage-agent)

---

### 🧠 PCOS × Neurodivergence RAG Assistant
> `Python` `LangChain` `FAISS` `Groq LLaMA 3.1` `HuggingFace MiniLM` `ipywidgets`

RAG pipeline grounded in peer-reviewed clinical papers on PCOS and neurodivergence co-occurrence — an underresearched intersection that affects a lot of people who don't have good answers. Hallucination-aware system prompt forces refusal when context is insufficient. Built because the question mattered, not because it was easy.

**Result: Answers complex clinical questions with exact source citations, refuses when grounding is absent**

🔗 [Repo](https://github.com/mistyvisty/pcos-neurodivergence-rag) · 📝 [Medium write-up](https://medium.com/@bhardwajpreeti357/i-built-an-ai-that-reads-clinical-research-papers-and-answers-questions-about-pcos-and-b1f526784409)

---

### 🏥 Hospital Readmission Risk Predictor
> `Python` `XGBoost` `SMOTE` `SHAP` `FastAPI` `Docker` `GitHub Actions CI/CD`

Production-style ML pipeline on 101,766 patient records. Removed target-leaking features (variables only knowable after the outcome), SMOTE inside ImbPipeline to prevent synthetic data leaking into validation folds, served via FastAPI with Pydantic schemas, containerized with Docker, deployed via automated CI/CD.

**Result: Mean CV AUC 0.581 — reported honestly, consistent with published benchmarks for this genuinely hard problem**

🔗 [Repo](https://github.com/mistyvisty/hospital-readmission-predictor) · 🚀 [Live App](https://hospital-readmission-bz7hqjeye7fgsppfs3pwqm.streamlit.app/)

---

### 🩺 PCOS Detection & Risk Prediction
> `Python` `XGBoost` `Random Forest` `SHAP` `SMOTE` `ImbPipeline` `5-Fold Stratified CV`

ML pipeline on 541 records from 10 hospitals. Engineered `Total_follicles` feature — became the #1 SHAP predictor, above either individual follicle count. Zero data leakage across 5-fold stratified CV. Threshold tuned for recall > 90% because false negatives (missed PCOS) are clinically worse than false positives.

**Result: Random Forest Mean AUC 0.973 · Recall 91.4% at tuned threshold**

🔗 [Notebook](https://github.com/mistyvisty/Data-Analytics-Portfolio/blob/main/PCOS_Detection_Medical.ipynb)

---

### 🤖 Medical RAG Assistant — PCOS Clinical Literature
> `Python` `LangChain` `FAISS` `HuggingFace MiniLM` `Groq LLaMA 3.1`

RAG pipeline on PubMed PCOS literature. 361 chunks, MiniLM embeddings, FAISS retrieval, hallucination-aware system prompt that refuses out-of-context queries and requires exact source + page citations on every answer.

🔗 [Notebook](https://github.com/mistyvisty/Data-Analytics-Portfolio/blob/main/Medical_RAG_Assistant.ipynb)

---

### 🏦 Bank Customer Churn Prediction
> `Python` `XGBoost` `SHAP Beeswarm` `ImbPipeline` `5-Fold CV`

Caught a target-leaking feature (Complain, 0.996 correlation with churn — but only knowable after the customer already churned). Removed it. Used SHAP Beeswarm to surface Age and NumOfProducts as real predictors. Identified Germany as highest-risk market.

**Result: XGBoost ROC-AUC 0.847 · Recommended Germany-specific retention strategy**

🔗 [Notebook](https://github.com/mistyvisty/Data-Analytics-Portfolio/blob/main/Bank_Customer_Churn_Prediction.ipynb)

---

### 📊 AI CSV Analyst — Conversational Data Copilot
> `Python` `Streamlit` `Groq LLaMA 3.3-70B` `Pandas` `Matplotlib`

Deployed full-stack copilot that lets non-technical users query raw CSVs in plain English with auto-rendered charts. Custom truncation algorithm handles datasets up to 200MB by preserving structural context while staying within context-window limits.

🔗 [Repo](https://github.com/mistyvisty/ai_csv_analyst) · 🚀 [Live App](https://preeti-ai-csv-analyst.streamlit.app/)

---

## 📝 Latest Writing

- [Why I Built a PCOS Prediction Model — And Why It Was Never Just a Portfolio Project](https://medium.com/@bhardwajpreeti357/why-i-built-a-pcos-prediction-model...)
- [I Built an AI That Reads Clinical Research Papers and Answers Questions About PCOS and Neurodivergence](https://medium.com/@bhardwajpreeti357/i-built-an-ai-that-reads-clinical-research-papers...)

---

## 📚 Currently Studying

Live reading notes on ML/GenAI interview prep — updated as I study:
- 📖 [Notion Live Notes](https://spiral-game-e5b.notion.site/ML-Interview-Prep-Live-Reading-Notes-566ee8267299463b90dbe8c04434e496) — Chip Huyen's ML Interviews Book + Grokking ML
- 💻 [ml-study-notes repo](https://github.com/mistyvisty/ml-study-notes) — markdown notes + study guide

---

*Open to Data Scientist / GenAI Engineer / ML Engineer roles*
