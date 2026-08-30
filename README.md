# AI-Based Credit Bureau Complaint Classification System

## 📌 Project Overview

The AI-Based Credit Bureau Complaint Classification System is a Machine Learning and Natural Language Processing project designed to automatically classify customer complaints into appropriate Issue Categories.

The system analyzes the complaint text submitted by customers and predicts the category of the issue being discussed.

For example:

**Complaint:**
> My personal information and address are incorrect in my credit report.

**Predicted Issue Category:**
> Personal Information

---

## 🎯 Problem Statement

Credit bureau organizations receive a large number of customer complaints and Voice of Customer (VOC) records.

Manually reading and categorizing these complaints can be:

- Time-consuming
- Difficult to scale
- Prone to human errors

This project aims to automate the complaint classification process using Machine Learning and Natural Language Processing techniques.

---

## 💡 Solution

The system uses customer complaint text as input and predicts the corresponding **Issue Category**.

The Machine Learning workflow includes:

1. Data Collection
2. Data Cleaning
3. Text Preprocessing
4. Feature Extraction using TF-IDF
5. Model Training
6. Model Evaluation
7. Complaint Category Prediction
8. Streamlit Deployment

---

## 📊 Dataset

The dataset contains Credit Bureau customer complaints and Voice of Customer (VOC) records.

Important columns include:

- Complaint_ID
- Complaint_Text
- Issue_Category

### Target Variable

The target variable used for Machine Learning classification is:

`Issue_Category`

The objective is to identify what issue the customer is mainly discussing in the complaint.

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing (NLP)
- TF-IDF Vectorizer
- Logistic Regression
- Matplotlib
- Seaborn
- Streamlit
- Joblib
- Jupyter Notebook

---

## 🔄 Project Workflow

```text
Customer Complaint
       │
       ▼
Data Cleaning
       │
       ▼
Text Preprocessing
       │
       ▼
TF-IDF Vectorization
       │
       ▼
Train-Test Split
       │
       ▼
Logistic Regression Model
       │
       ▼
Model Evaluation
       │
       ▼
Issue Category Prediction
       │
       ▼
Streamlit Deployment
