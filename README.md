<div align="center">

# Hi, I'm Preeti Bhardwaj 👋

### Data Analyst · Machine Learning Enthusiast · 

*Turning messy data into clear decisions — one pipeline at a time.*

[![Portfolio](https://img.shields.io/badge/📂_Portfolio-mistyvisty.github.io-1F4E79?style=for-the-badge)](https://mistyvisty.github.io)
[![Email](https://img.shields.io/badge/📧_Email-bhardwajpreeti357@gmail.com-D44638?style=for-the-badge)](mailto:bhardwajpreeti357@gmail.com)


</div>

---

## 👩‍💻 About Me

Hii i'm Preeti Bhardwaj
I'm a **Data Analyst and Machine Learning Enthusiast** with hands-on experience building end-to-end analytics projects across **Medical AI, Banking, and Retail** domains.

- 🔬 I love finding the story hidden inside complex datasets
- 🧠 Passionate about *Machine Learning and Data Analysis*
- 📊 I bridge the gap between raw data and business decisions
- 🎓 B.Tech in Electronics & Communication Engineering
- 🚀 Actively looking for **Data Analyst roles** as a Machine Learning Enthusiast

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**ML & Data**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-Explainability-6A0DAD?style=flat-square)
![SMOTE](https://img.shields.io/badge/SMOTE-ImbLearn-E76F51?style=flat-square)

**GenAI & RAG**

![LangChain](https://img.shields.io/badge/LangChain-000000?style=flat-square&logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-Vector_Search-0066CC?style=flat-square)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Groq](https://img.shields.io/badge/Groq-LLaMA_3.1-F54F29?style=flat-square)

**Visualization**

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)

**Tools & Deployment**

![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

---

## 📂 Featured Projects

### 🩺 PCOS Detection & Risk Prediction
> Medical AI | Python · XGBoost · SHAP · SMOTE · ImbPipeline · 5-Fold CV

Built an end-to-end ML pipeline on 541 patient records from 10 hospitals. Implemented SMOTE inside ImbPipeline for **zero data leakage**, applied threshold tuning to maximize recall, and used SHAP to explain predictions.

**✅ Result: Random Forest achieved Mean AUC 0.97 across 5 folds — catching 90%+ PCOS patients**

🔗 [View Notebook](https://github.com/mistyvisty/Data-Analytics-Portfolio/blob/main/PCOS_Detection_Medical.ipynb)

---

### 🏦 Bank Customer Churn Prediction
> Banking | Python · XGBoost · SHAP Beeswarm · ImbPipeline · 5-Fold CV

Analyzed 10,000 customer records to predict churn. Identified Germany as a critical churn market (32.4% rate), removed a leaky feature (Complain, 0.996 correlation), and used SHAP Beeswarm to reveal Age and NumOfProducts as top drivers.

**✅ Result: XGBoost ROC-AUC 0.847 | Recommended Germany-specific retention campaign**

🔗 [View Notebook](https://github.com/mistyvisty/Data-Analytics-Portfolio/blob/main/Bank_Customer_Churn_Prediction.ipynb)

---

### 🛒 Superstore Sales Analysis (SQL + Power BI)
> Retail | SQLite · 12 SQL Queries · Power BI Dashboard

Wrote 12 business SQL queries on 9,994 retail orders. Discovered $125K in annual losses from high-discount orders using CASE WHEN analysis. Built an interactive Power BI dashboard with KPI cards, region map, and trend charts.

**✅ Result: Recommended capping discounts at 20% to recover $125K annually**

🔗 [View Notebook](https://github.com/mistyvisty/Data-Analytics-Portfolio/blob/main/Superstore_Sales_SQL_Analysis.ipynb)

---

### 🏥 Hospital Readmission Risk Predictor
> Healthcare AI / MLOps | Python · XGBoost · SMOTE · SHAP · FastAPI · Docker · GitHub Actions CI/CD

End-to-end production ML pipeline predicting 30-day hospital readmission risk on 101,766 patient records (UCI Diabetes 130-US Hospitals dataset). Built with SMOTE inside ImbPipeline, 5-fold cross-validation, precision-recall threshold tuning, and SHAP explainability — fully containerized with Docker and deployed via automated GitHub Actions CI/CD.

**✅ Result: Mean CV AUC 0.581, consistent with published benchmarks (0.64–0.67) for this genuinely hard clinical prediction problem — reported honestly rather than inflated**

🔗 [View Repo](https://github.com/mistyvisty/hospital-readmission-predictor)

---

### 🤖 Medical RAG Assistant — PCOS Clinical Literature
> Medical AI / Generative AI | Python · LangChain · FAISS · HuggingFace · Groq (LLaMA 3.1)

Built a RAG pipeline grounded in real PCOS research papers. Features a hallucination-aware prompt that refuses to answer when context is missing, and provides source citations with page numbers on every answer.

**✅ Result: Answers clinical PCOS questions with cited evidence from uploaded research papers**

🔗 [View Notebook](https://github.com/mistyvisty/Data-Analytics-Portfolio/blob/main/Medical_RAG_Assistant.ipynb)

---

### 📊 AI CSV Analyst — Chat with Your Data
> Generative AI / Data Analysis | Python · Streamlit · Groq (LLaMA 3.1) · Pandas · Matplotlib

Upload any CSV and ask questions in plain English — AI generates insights and auto-renders charts. Fully deployed as a live app on Streamlit Cloud, available for anyone to use with their own data.

**✅ Result: Fully deployed live app — anyone can use it with their own CSV**

🔗 [View Repo](https://github.com/mistyvisty/ai_csv_analyst) · 🚀 [Live Demo](https://preeti-ai-csv-analyst.streamlit.app/)

---

I believe the same curiosity that drives me to explore datasets also drives me to explore the world. 🌏

---

<div align="center">

*If you find my work interesting, feel free to ⭐ the portfolio repo or reach out — I'd love to connect!*

📧 **bhardwajpreeti357@gmail.com**
🔗 **[github.com/mistyvisty/Data-Analytics-Portfolio](https://github.com/mistyvisty/Data-Analytics-Portfolio)**
🌐 **[mistyvisty.github.io](https://mistyvisty.github.io)**

</div>
