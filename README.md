# Smoker Lung Cancer Stage Detection & Prediction Model
This repository presents a comprehensive comparative analysis and research documentation for detecting and predicting lung cancer stages in smokers using various Machine Learning algorithms.
## 📌 Project Overview
The primary objective of this project is to evaluate and compare multiple machine learning classifiers to accurately predict lung cancer risk levels (Low, Medium, High) based on patient demographics, biological factors, environmental exposures, and early symptoms.
## 📊 Dataset & Features
The model evaluates several critical risk factors and clinical symptoms, including:
* **Demographics & Lifestyle:** Age, Gender, Smoking Habits, Passive Smoking, Alcohol Use, Obesity, Diet.
* **Environmental & Occupational:** Air Pollution, Dust Allergy, Occupational Hazards.
* **Medical History & Symptoms:** Genetic Risk, Chronic Lung Disease, Chest Pain, Coughing of Blood, Fatigue, Weight Loss, Shortness of Breath, Wheezing, Swallowing Difficulty, Dry Cough, Snoring.
---
## ⚙️ Model Performance & Evaluation
The dataset was preprocessed and split using a **70/30 Train-Test ratio**. Five distinct classification algorithms were trained, tested, and evaluated across multiple performance metrics.

| Model | Accuracy | Precision | Recall | F1-Score |
| :--- | :--- | :--- | :--- | :--- |
| **Gradient Boosting Classifier** | **100.00%** | **100%** | **100%** | **100%** |
| **Decision Tree Classifier** | **100.00%** | **100%** | **100%** | **100%** |
| **Support Vector Machine (SVM)** | **95.33%** | 100% | 100% | 97% |
| **K-Nearest Neighbors (KNN)** | **93.67%** | 99% | 100% | 98% |
| **Logistic Regression** | **90.33%** | 97% | 100% | 98% |

### 🔄 5-Fold Cross-Validation Accuracy
* **Gradient Boosting & Decision Tree:** 100.0%
* **K-Nearest Neighbors (KNN):** 99.8%
* **Support Vector Machine (SVM):** 94.9%
* **Logistic Regression:** 94.3%
---
## 🔍 Key Predictors & Feature Importance
Based on feature correlation analysis with the target classification level, the top 10 factors influencing lung cancer risk predictions are:
1. **Coughing of Blood** *(Highest Correlation)*
2. **Dust Allergy**
3. **Passive Smoking**
4. **Occupational Hazards**
5. **Air Pollution**
6. **Chronic Lung Disease**
7. **Shortness of Breath**
8. **Dry Cough**
9. **Snoring**
10. **Swallowing Difficulty**
---
## 💡 Key Conclusions
* **Gradient Boosting** and **Decision Tree** models yielded superior diagnostic precision, making them highly effective candidate algorithms for automated clinical risk assessment tools.
* High correlation factors such as *Coughing of Blood*, *Dust Allergy*, and *Passive Smoking* play pivotal roles in early detection.
---
> **Note:** This repository serves as the analytical case study and documentation of the model's evaluation. The full report is available in the repository as a PDF (`Lung_Cancer_Detection_Report.pdf`).
