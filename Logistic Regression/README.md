# 📩 Email Spam Detection using Logistic Regression

## 📌 Project Overview
This project implements an **Email Spam Detection system** using **Logistic Regression**, a powerful and interpretable binary classification algorithm.  
The model predicts whether a given email/message is **Spam** or **Ham (Not Spam)** based on textual content.

The project focuses on:
- Text preprocessing
- Feature extraction using TF-IDF
- Probabilistic classification
- Model interpretability and evaluation

---

## 🎯 Problem Statement
Email spam is a major issue that affects productivity and security.  
The goal of this project is to build a machine learning model that can **accurately classify messages as spam or ham**, while minimizing false positives.

---

## 🧠 Why Logistic Regression?
- Well-suited for **binary classification**
- Produces **probability-based outputs**
- Highly **interpretable**
- Lightweight and production-friendly

---

## 📂 Dataset
**SMS Spam Collection Dataset**  
- Source: UCI Machine Learning Repository / Kaggle  
- Records: 5,500+ messages  

### Columns:
- `label` → spam / ham (target)
- `message` → text content

Although the dataset contains only two columns, text vectorization transforms the message column into thousands of numerical features.

---

## ⚙️ Project Workflow
1. Data loading & cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature engineering (message length)  
4. Text vectorization using TF-IDF  
5. Logistic Regression model training  
6. Model evaluation  
7. User-based text prediction  

---

## 📊 Model Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC Curve

Special emphasis is placed on **precision vs recall tradeoff**, which is critical in spam detection systems.

---

## 🔮 User Input Prediction
The model allows users to input custom text and returns:
- Spam / Ham label
- Spam probability score

This simulates a real-world email filtering system.

---

## 🛠️ Technologies Used
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- TF-IDF Vectorization

---

## 🚀 Future Improvements
- Threshold tuning for cost-sensitive classification
- Advanced NLP preprocessing
- Model comparison with Naive Bayes & SVM
- Deployment using Streamlit

---

## 📌 Conclusion
This project demonstrates how Logistic Regression can be effectively used for real-world text classification tasks, providing both strong performance and interpretability.

---

⭐ If you find this project useful, feel free to star the repository!

