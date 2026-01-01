# 📊 Instagram Reach Prediction Using Linear Regression

## 📌 Project Overview
This project focuses on **predicting Instagram post reach** based on **content characteristics**, specifically **media type** and **hashtag count**.  
A **Linear Regression model** is used as a baseline to understand how these factors influence reach.

---

## 🎯 Project Objective
- Analyze the impact of **media type** and **hashtag usage** on Instagram reach  
- Build a regression-based model to **predict reach**  
- Allow **user input** for media type and hashtag count to generate predictions  

---

## 🧠 Problem Statement
> How can we estimate the reach of an Instagram post using content-level attributes such as media type and hashtag strategy?

---

## 🗂 Dataset Description
The dataset contains cleaned Instagram post data with the following relevant columns:

- `media_type` (categorical): image, video, reel, carousel  
- `hashtag_count` (numerical): number of hashtags used  
- `reach` (numerical): total reach of the post  

Data cleaning and exploratory analysis were performed before modeling.

---

## ⚙️ Methodology
1. **Data Cleaning & EDA**
   - Removed inconsistencies and missing values  
   - Created visualizations to identify trends  

2. **Feature Engineering**
   - Selected `media_type` and `hashtag_count` as predictors  

3. **Encoding & Scaling**
   - Applied **One-Hot Encoding** to media types  
   - Scaled numerical features using `StandardScaler`  

4. **Modeling**
   - Used **Linear Regression** as a baseline model  
   - Implemented preprocessing and modeling using a **Scikit-learn Pipeline**

5. **Prediction**
   - Took user input for media type and hashtag count  
   - Predicted Instagram reach in real time  

---

## 🧪 Model Evaluation
The model was evaluated using:
- **R² Score**
- **Mean Absolute Error (MAE)**

Linear Regression provides interpretability but may not fully capture Instagram’s non-linear behavior.

---

## 📈 Key Insights
- Media type significantly influences reach  
- Hashtag count has a moderate effect  
- Linear Regression serves as a strong baseline but can be improved with advanced models  

---

## 🛠 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn (for EDA)  

---

## 🚀 Future Improvements
- Add features like followers count, impressions, posting time  
- Experiment with non-linear models (Random Forest, XGBoost)  
- Deploy the model using **Streamlit** or **Flask**

---


---

## 📌 Conclusion
This project demonstrates how **content attributes** can be leveraged to predict Instagram reach using a structured machine learning workflow. It highlights the importance of **feature engineering and encoding** in regression-based problems.

---

## 🤝 Connect
If you have feedback or suggestions, feel free to connect with me on LinkedIn or explore the project further.


