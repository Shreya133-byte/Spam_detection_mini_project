# 📧 SMS Spam Detector

A Machine Learning based SMS Spam Detection system that classifies text messages as **Spam** or **Ham (Legitimate)** using **TF-IDF feature extraction** and a **Linear Support Vector Machine (SVM)** classifier.

The project uses the **UCI SMS Spam Collection** dataset and includes data analysis, text preprocessing, model comparison, hyperparameter tuning, error analysis, model saving, and a simple Gradio web interface.

---

## 🚀 Project Overview

Spam messages are a common form of unwanted communication and can sometimes contain fraudulent links, advertisements, or malicious content.

This project builds a machine learning pipeline that automatically analyzes an SMS message and predicts whether it is:

- ✅ **Ham** — Legitimate message
- 🚨 **Spam** — Unwanted or suspicious message

The final model uses **TF-IDF + Linear SVM** and achieved approximately **98.65% accuracy** and **94.85% F1-score** on the held-out test set.

---

## 🎯 Objectives

- Detect spam SMS messages automatically.
- Preprocess and clean raw text data.
- Convert text into numerical features using TF-IDF.
- Compare multiple machine learning algorithms.
- Tune the best-performing model.
- Analyze incorrect predictions.
- Save the trained model for future predictions.
- Build a simple interactive web interface using Gradio.

---

## 📊 Dataset

The project uses the **UCI SMS Spam Collection** dataset.

**Dataset:** SMS Spam Collection  
**Source:** UCI Machine Learning Repository  
**Number of messages:** 5,572 originally  
**Classes:**

| Label | Meaning |
|---|---|
| `ham` | Legitimate SMS |
| `spam` | Spam SMS |

Two messages containing only emoticons became empty after text cleaning and were removed from the modeling dataset, resulting in **5,570 usable messages**.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Gradio
- Google Colab
- Jupyter Notebook

---

## 🧠 Machine Learning Workflow

```text
SMS Dataset
     ↓
Data Understanding
     ↓
Exploratory Data Analysis
     ↓
Text Preprocessing
     ↓
Train/Test Split
     ↓
TF-IDF Feature Extraction
     ↓
Model Training
     ↓
Model Comparison
     ↓
Hyperparameter Tuning
     ↓
Error Analysis
     ↓
Final Linear SVM Model
     ↓
Gradio Prediction Interface
