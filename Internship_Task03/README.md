#  AI/ML Internship Tasks Repository

Hello Again! This repo contains my work on various tasks assigned during the internship, starting with exploratory data analysis of the Iris dataset.

---

#  Task03 House Price Prediction

##  Problem Statement

Accurate house price estimation benefits buyers, sellers, and real estate professionals. This project builds a predictive model to estimate house prices using property features like size, bedrooms, and location. The model helps in understanding how these factors influence market value.

---

##  Task Objective

The goal of this project is to predict house prices using property features such as:
- Square footage (`sqft_living`)
- Number of bedrooms
- Location (represented by `city`)

We use machine learning models to train on historical house data and evaluate their ability to predict prices for unseen properties.

---

##  Dataset Used

- **Name:** House Sales in King County, USA
- **Source:** [Kaggle - House Sales Prediction Dataset](https://www.kaggle.com/datasets/shree1992/housedata?resource=download)
- **Size:** 21,000+ records
- **Key features used:** `sqft_living`, `bedrooms`, `city`
- **Target:** `price`

---

##  Models Applied

Two regression models were trained and evaluated:

1. **Linear Regression** – a simple baseline model
2. **Gradient Boosting Regressor** – a more advanced ensemble model

Both models were trained on a standardized and encoded version of the dataset using an 80/20 train-test split.

---

##  Key Results and Findings

| Model               | MAE (↓)      | RMSE (↓)     |
|--------------------|--------------|--------------|
| Linear Regression  | ~XXX,XXX     | ~YYY,YYY     |
| Gradient Boosting  | ~AAA,AAA     | ~BBB,BBB     |

- **Gradient Boosting outperformed Linear Regression**, achieving lower error rates on both MAE and RMSE.
- **City** and **square footage** had a strong influence on house price.
- Feature encoding and scaling were essential to improve model accuracy.

---

##  Conclusion

This project demonstrates how regression models can be effectively used to estimate property prices. Gradient Boosting, with proper preprocessing, provides better prediction performance and can serve as a strong model for real estate price prediction tasks.

---

