#  Spam Email Detection System  
---

##  Overview  
Spam email detection is an important application of Machine Learning used to filter unwanted or harmful messages. 
This project implements a system that classifies emails into **Spam** and **Non-Spam (Ham)** using **Natural Language Processing (NLP)** and **Logistic Regression**.

---

##  Key Concepts Used  

- 📬 Email Filtering  
- 🧾 Text Classification  
- 🧠 Machine Learning  
- 🗣 Natural Language Processing (NLP)  
- ⚙️ Feature Engineering  

---

## 🛠️ Technologies & Libraries  

- Python   
- Pandas  
- NumPy  
- Regex (`re`)  
- NLTK  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 📂 Dataset  

- Dataset Source: Kaggle  
- 🔗 https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset  

This dataset contains labeled SMS messages categorized as **spam** or **ham**.

---

## ⚙️ Project Workflow  

1. **Data Collection**  
   - Load dataset from CSV file  

2. **Data Preprocessing**  
   - Remove special characters  
   - Convert text to lowercase  
   - Tokenization  
   - Stopword removal  

3. **Feature Extraction**  
   - TF-IDF Vectorization  

4. **Model Training**  
   - Logistic Regression model  

5. **Model Evaluation**  
   - Accuracy  
   - Precision  
   - Recall  
   - F1-score  

6. **Visualization**  
   - Confusion Matrix using heatmap  

7. **Model Saving**  
   - Saved using Pickle (`model.pkl`, `vectorizer.pkl`)  

---

## 📊 Model Performance  

- ✅ Accuracy: **95%**  
- 📌 High precision in spam classification  
- 📉 Balanced F1-score  

---






