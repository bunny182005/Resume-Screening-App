# 🧠 Resume Screening App using NLP | AI-Powered Resume Analyser

## 📋 Overview
The **Resume Screening App** is an AI-driven project built with **Python and Natural Language Processing (NLP)** that automatically analyzes and classifies resumes based on their content, skills, and experience.  
It helps recruiters and HR professionals streamline the hiring process by **shortlisting candidates efficiently** from large datasets.

This project demonstrates how NLP and Machine Learning can be applied to real-world recruitment problems — converting raw resume text into structured, meaningful insights.

---

## 🚀 Features
- 📄 **Resume Text Extraction:** Reads and parses resume content from `.pdf`, `.docx`, or `.txt` formats.  
- 🧹 **Text Preprocessing:** Cleans and normalizes text using tokenization, stopword removal, and lemmatization.  
- 🧠 **Machine Learning Classification:** Categorizes resumes into predefined domains (e.g., Data Science, Web Development, HR, etc.).  
- 🧩 **TF-IDF Vectorization:** Converts textual data into numerical vectors for model training.  
- 🔍 **Keyword Extraction:** Identifies and highlights key technical and soft skills from resumes.  
- 📊 **Model Evaluation:** Displays accuracy, confusion matrix, and performance metrics.  
- 🌐 **(Optional)** Streamlit-based UI for easy interaction and resume upload.

---

## 🧰 Tech Stack
**Language:**  
- Python 🐍  

**Libraries & Tools:**  
- `pandas`, `numpy` – Data handling and preprocessing  
- `nltk`, `spacy` – Natural Language Processing  
- `scikit-learn` – Machine learning model building  
- `pickle` – Model saving and loading  
- `streamlit` – Web app interface (optional)  

**Dataset:**  
- [Kaggle Resume Dataset](https://www.kaggle.com/datasets) or custom dataset  

---

## ⚙️ How It Works
1. **Data Loading:** Import the dataset containing resumes and categories.  
2. **Preprocessing:** Clean and tokenize text using NLP.  
3. **Feature Extraction:** Convert text into TF-IDF features.  
4. **Model Training:** Train a classifier (e.g., Logistic Regression, Naive Bayes, SVM).  
5. **Prediction:** Classify new resumes uploaded by the user.  
6. **Evaluation:** Assess accuracy and visualize metrics.  

---

## 💻 Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/bunny182005/Resume-Screening-App.git
cd Resume-Screening-App
