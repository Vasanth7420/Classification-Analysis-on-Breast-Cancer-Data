# 🩺 BREAST CANCER ANALYSIS  
*A Machine Learning Approach for Early Prediction of Breast Cancer*

This project focuses on diagnosing breast cancer using various machine learning classification models. It includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and performance comparison of six popular classifiers.

---

## 📁 Dataset  
- **Source:** [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
- **Features:** 30 numeric features computed from digitized images of breast masses
- **Target:** `diagnosis` — Malignant (M) or Benign (B)

---

## 🎯 Project Objectives  
- Clean and preprocess the breast cancer data  
- Visualize data distribution, correlations, and patterns  
- Train multiple classification models  
- Compare models using evaluation metrics (Accuracy, Precision, Recall, F1-score)  
- Visualize model performance for better interpretation  

---

## 📊 Visualizations Included  
- Count Plot of diagnosis classes  
- Histograms and Subplots  
- Scatter Plot  
- Boxplot and Violin Plot  
- Correlation Heatmap  
- Pair Plot  
- Bar Plot comparing model accuracies  

---

## 🤖 Machine Learning Models Used  
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Naive Bayes  
- Decision Tree  
- Random Forest  

---

## 🧪 Evaluation Results  
| Model              | Accuracy | Precision | Recall | F1 Score |
|-------------------|----------|-----------|--------|----------|
| Logistic Regression | 0.9649  | 0.9487    | 0.9487 | 0.9487   |
| KNN                 | 0.9561  | 0.9474    | 0.9231 | 0.9351   |
| SVM                 | 0.9298  | 0.9494    | 0.9070 | 0.9221   |
| Naive Bayes         | 0.9649  | 0.9733    | 0.9535 | 0.9619   |
| Decision Tree       | 0.9474  | 0.9302    | 0.9302 | 0.9302   |
| Random Forest       | 0.9649  | 0.9756    | 0.9302 | 0.9524   |

> ℹ️ *Note: Please update the table with your actual output if the results vary.*

---

## 📌 Conclusion  
This project highlights the effectiveness of multiple machine learning techniques in medical diagnosis.  
**Random Forest** and **Support Vector Machine** performed best in terms of **accuracy** and **F1-score**.  
Proper data preprocessing and feature selection play a crucial role in boosting model performance.

---

## 🛠️ Requirements  
Make sure the following libraries are installed:

```bash
Python 3.x  
pandas  
numpy  
matplotlib  
seaborn  
scikit-learn
