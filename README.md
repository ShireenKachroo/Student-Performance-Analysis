# 🎓 Student Performance Analysis

This project analyzes the **Student Performance Dataset** using different machine learning algorithms to predict student outcomes and gain insights into factors affecting academic performance.  

---

## 📂 Dataset
The dataset contains information about students, including:
- Demographics (age, gender, parental education)
- Study-related attributes (study time, failures, absences)
- Grades and performance metrics (G1, G2, G3)

Dataset source: [Student Performance](https://raw.githubusercontent.com/arunk13/MSDA-Assignments/master/IS607Fall2015/Assignment3/student-mat.csv)

---

## 🚀 Algorithms Used
1. **Logistic Regression** – Predict pass/fail outcomes  
2. **Decision Tree Classifier** – Simple interpretable model for performance prediction  
3. **Random Forest Classifier** – Ensemble method for better accuracy  

---

## ⚙️ Steps
1. Data preprocessing (handling categorical & numerical features)  
2. Train-test split  
3. Training models (Logistic Regression, Decision Tree, Random Forest)  
4. Model evaluation using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix  

---

## 📊 Results
- Logistic Regression: Baseline performance  
- Decision Tree: Better interpretability, moderate accuracy  
- Random Forest: Best overall performance with highest accuracy  

---

## 📌 Requirements
Install dependencies with:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
