# 🩺 AI-Based Medical Diagnosis Assistant (Python, ML)

An **AI-powered Medical Diagnosis Assistant** that predicts diseases based on user-reported symptoms and suggests relevant treatments. Built using **Python, Scikit-Learn, and Random Forest Classifier**, the system provides preliminary health insights to promote early awareness and informed decision-making.

---

## ✨ Features

### 📊 Machine Learning
- Uses **Random Forest Classifier** trained on a curated symptom–disease dataset.
- Predicts the **most likely disease** and provides **top 3 probable diseases** with confidence scores.

### 👤 Symptom Input
- Collects patient details (name, age, gender).
- Accepts multiple symptoms as input.
- Standardizes input to match dataset format.

### 🧾 Diagnosis & Treatment
- Predicts the disease from given symptoms.
- Suggests relevant treatments from a mapped dataset.
- Provides default suggestions if no exact match is found.

### 📑 Reporting Module
- Generates a **detailed diagnosis report**:
  - Patient details
  - Predicted disease
  - Confidence scores
  - Suggested treatments

### ⚠️ Error Handling & Validation
- Validates symptom input.
- Handles missing files and runtime errors gracefully.

---

## 🛠 Tools & Technologies
- **Python**
- **Scikit-Learn (Random Forest Classifier)**
- **Pandas (Data Handling & Cleaning)**
- **Google Colab (Model Training & Testing)**
- **Datasets**:  
  - `Training.csv` – Symptom-disease mapping  
  - `Diseases_Symptoms.csv` – Disease-treatment mapping  

---
