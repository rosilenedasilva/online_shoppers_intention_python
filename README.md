# 🛒 Online Shoppers' Intention Prediction

## 🔍 Project Overview

This project analyses user behaviour on an e-commerce website to predict whether a visitor will make a purchase (**Revenue = True/False**).
The analysis combines exploratory data analysis (EDA) and machine learning to identify patterns and key factors influencing purchasing decisions.

---

## 📊 Dataset

The dataset is based on the **Online Shoppers Purchasing Intention Dataset**, which contains session-level data for **12,330 users** over a one-year period ([Kaggle][1])

### Key characteristics:

* 10 numerical and 8 categorical features ([Kaggle][1])
* Each row represents a unique user session
* Target variable: **Revenue (purchase or not)**
* Includes behavioural metrics such as:

  * Page visits and duration
  * Bounce rates and exit rates
  * Traffic source and visitor type

---

## 🛠 Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn
* Jupyter Notebook

---

## 📈 Analysis Performed

### 1. Exploratory Data Analysis (EDA)

* Examined user behaviour patterns across sessions
* Identified key variables influencing purchase decisions
* Analysed distribution of categorical and numerical features
* Observed class imbalance (majority non-purchasing users)

---

### 2. Feature Analysis

* Investigated relationships between session features and revenue
* Identified important predictors such as:

  * Page value
  * Exit rate
  * Time spent on product-related pages

👉 These features are known to strongly impact purchase intention ([ubc-mds.github.io][2])

---

### 3. Machine Learning Model

* Built a classification model to predict purchase intention
* Evaluated model performance using standard metrics
* Addressed class imbalance in the dataset

👉 Predicting purchase intent is a key problem in e-commerce analytics, helping businesses improve conversion rates ([PMC][3])

---

## 📓 Notebook

👉 `ecommerce_revenue_prediction.ipynb`

---

## 🚀 Project Highlights

* Performed end-to-end data analysis (EDA → modeling)
* Identified behavioural drivers of customer purchases
* Built a predictive model for revenue generation
* Demonstrated practical application of machine learning in e-commerce

---

## 📌 Key Takeaways

* User behaviour metrics are strong indicators of purchase intent
* Time spent and engagement significantly influence conversions
* Machine learning can effectively support decision-making in online retail

---

## 📁 Repository Structure

```bash
├── ecommerce_revenue_prediction.ipynb
├── data/
│   └── online_shoppers_intention.csv
├── README.md
```

---

## 📎 Notes

* Dataset included for reproducibility
* Notebook optimised for clarity and readability
* This project demonstrates both **data analysis** and **machine learning skills**
* 
