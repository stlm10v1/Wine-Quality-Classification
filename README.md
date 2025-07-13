# 🍷 Wine Quality Classification using Machine Learning

This project explores and models wine quality prediction using red and white wine datasets. It was completed as part of the **Data Mining and Knowledge Discovery** course at **IIT Kanpur**.

---

## 📌 Project Objectives

- Combine and analyze red and white wine datasets.
- Perform classification to predict **wine type or quality** based on chemical properties.
- Apply various machine learning models and compare their performance.
- Handle class imbalance using **SMOTE**.
- Apply clustering to explore data patterns using **KMeans**.

---

## 🧰 Techniques and Algorithms Used

- **Data Preprocessing**:
  - Min-Max Scaling
  - Standard Scaling
  - Class balancing using **SMOTE**
- **Classification Models**:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest
  - Support Vector Machine (SVM)
  - Naive Bayes (Gaussian, Multinomial)
  - Bagging Classifier
- **Clustering**:
  - KMeans for unsupervised pattern discovery
- **Model Evaluation**:
  - Confusion Matrix
  - Classification Report
  - Cross-validation
  - Grid Search for hyperparameter tuning

---

## 📂 Files Included

- `project_Final.ipynb` – Full analysis, modeling, and evaluation code
- `winequality-red.csv` – Red wine dataset (from UCI repository)
- `winequality-white.csv` – White wine dataset
- `README.md` – Project documentation

---

## 🔍 Key Insights

- Proper preprocessing (normalization and class balancing) significantly improves model performance.
- Ensemble models like **Random Forest** and **Bagging** performed better than individual classifiers.
- KMeans clustering showed interesting groupings but requires domain-specific tuning for interpretability.

---

## 📈 Future Scope

- Deploy the model using Streamlit or Flask for prediction on new samples.
- Add PCA for dimensionality reduction and visualization.
- Use advanced ensemble techniques like XGBoost or Voting Classifiers.

---

## 👨‍💻 Author

**Vikram Anand**  
M.Tech (2025), Department of Management Sciences (DoMS)  
IIT Kanpur
