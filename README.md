# ML_PROJECT_Breast-Cancer
# 🧠 Breast Cancer Classification Using SVM and Neural Networks

This project applies machine learning techniques to classify breast cancer diagnoses using the Breast Cancer Wisconsin (Diagnostic) Dataset. Developed as part of my graduate coursework in Health Informatics at Rutgers University, it explores the performance of Support Vector Machines (SVM) and Neural Networks in clinical prediction tasks.

## 📌 Objectives

- Build and evaluate classification models using Python (SVM with linear and RBF kernels, MLPClassifier)
- Compare model performance across different train-test splits and feature selections
- Identify top predictive features and assess their impact on diagnostic accuracy

## 🧪 Methodology

- Data cleaning: handled missing values and standardized features
- Feature scaling with StandardScaler for model stability
- Trained models on full feature set, top two features, and top one feature
- Evaluated using accuracy, precision, recall, F1-score, confusion matrix, and ROC-AUC

## 📊 Key Findings

- Neural Networks and SVM (linear) consistently outperformed other models
- Reducing to top two features maintained high accuracy; using only one feature degraded performance
- Model robustness was confirmed across different random splits

## 🔍 Tools & Libraries

- Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
