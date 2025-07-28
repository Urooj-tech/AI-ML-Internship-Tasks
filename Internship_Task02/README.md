# Heart Disease Prediction

##  Problem Statement

The goal of this project is to build a machine learning model that predicts whether a person is at risk of heart disease based on their medical and health-related attributes. This can help in early diagnosis and preventive healthcare.

---

##  Task Objective

- Use a Logistic Regression model to predict the presence of heart disease.
- Evaluate the model using **Accuracy**, **Confusion Matrix**, and **ROC-AUC Curve**.

---

##  Dataset Used

- **Source**: [Kaggle - Heart Disease UCI Dataset](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)
- **File**: `heart.csv`
- **Attributes** include:
  - Age, Sex, Chest Pain Type, Resting BP, Cholesterol, Fasting Blood Sugar, Resting ECG, Max Heart Rate, Exercise Induced Angina, ST Depression, etc.
- **Target**: `target` (1 = has heart disease, 0 = no heart disease)

---

##  Models Applied

- **Logistic Regression**
  - Supervised binary classification model
  - Interpretable and widely used for medical diagnosis problems
---

##  Evaluation Metrics

- **Accuracy Score**
- **Confusion Matrix** (visualized using heatmap)
- **ROC Curve** and **AUC Score**

---

##  Key Results and Findings

- The model achieved an **accuracy of ~X%** *~79.5% (varies based on dataset)

- ROC Curve and AUC analysis shows the model is capable of distinguishing between positive and negative cases.
**ROC-AUC Score**: ~0.90 (indicating excellent separability between classes)

- Confusion matrix shows the number of true positives and true negatives predicted correctly.

---

##  Requirements

```bash
pandas
numpy
matplotlib
seaborn
scikit-learn
