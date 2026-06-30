# 🧠 AI-Based Resume Screening for Job Roles

A **machine learning–powered intelligent system** for automated resume screening, classification, and skill assessment.  
This project combines **BERT-based embeddings** with **custom feature extraction** and an **XGBoost classifier** to predict the most suitable job role for a given resume.

---

## 🚀 Overview

Traditional resume screening is time-consuming and prone to human bias.  
This project automates the process by leveraging **Natural Language Processing (NLP)** and **AI-based feature engineering** to classify resumes into specific job roles and generate skill-based analytics.

---

## 🧩 Core Features

| Feature | Description |
|----------|--------------|
| 🧠 **Transformer Embeddings (BERT)** | Uses `all-MiniLM-L6-v2` model from Sentence Transformers for contextual text encoding |
| 🧮 **XGBoost Classifier** | Classifies resumes into predefined job roles with high accuracy |
| 🧰 **4 Novel Features** | Extracts unique candidate insights such as experience, skills, resume quality, and candidate score |
| 📄 **Resume Parsing (PDF)** | Reads resumes directly from uploaded PDF files using `PyPDF2` |
| 📊 **Explainability** | Displays feature importance and confusion matrix for transparency |
| 💾 **Model Persistence** | Saves trained model, encoder, and evaluation metrics for reuse |
| 🌐 **GitHub Integration** | Pushes trained model and outputs to your GitHub repository directly from Colab |

---

## 🧠 Novel Feature Engineering

| Feature | Description |
|----------|--------------|
| 1️⃣ **Experience Extraction** | Detects and quantifies years of experience from resume text |
| 2️⃣ **Skill Categorization** | Identifies both technical and soft skills from multiple categories |
| 3️⃣ **Resume Quality Score** | Combines readability and structure for content quality evaluation |
| 4️⃣ **Candidate Score** | Weighted composite score combining skills, experience, and quality |

---

## ⚙️ Technologies & Libraries Used

### 🔬 **Core Libraries**
- `sentence-transformers` → for BERT embeddings  
- `xgboost` → classification model  
- `scikit-learn` → preprocessing, metrics, and label encoding  
- `nltk`, `textstat` → NLP and readability scoring  
- `pandas`, `numpy` → data manipulation and analysis  

### 🧰 **Utility Libraries**
- `matplotlib`, `seaborn` → visualization and confusion matrix plotting  
- `PyPDF2` → reading resume PDFs  
- `google.colab`, `joblib`, `json`, `os` → file handling and saving models  

---
Workflow-
Resume
      ↓

Text Cleaning
      ↓

TF-IDF
      ↓

XGBoost Model
      ↓

Predicted Job Role
      ↓

Experience Analysis
      ↓

Skill Extraction
      ↓

Skill Gap Analysis
      ↓

Resume Quality Score
      ↓

Candidate Fit Report

## 🧩 Installation

Run this in your Google Colab or local environment:

```bash
pip install sentence-transformers transformers xgboost scikit-learn pandas matplotlib seaborn PyPDF2 textstat nltk
