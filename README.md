# 🛒 Online Shoppers' Intention Prediction

## 🔍 Project Overview

This project analyses user behaviour on an e-commerce website to predict whether a visitor will make a purchase (**Revenue = True/False**).
The analysis combines exploratory data analysis (EDA) and machine learning to identify patterns and key factors influencing purchasing decisions.


## 📊 Dataset

The dataset used is the **Online Shoppers Purchasing Intention Dataset**, which contains session-level data for 12,330 users over a one-year period.

### Key characteristics:

* 10 numerical and 8 categorical features
* Each row represents a unique user session
* Target variable: **Revenue (purchase or not)**
* Includes behavioural metrics such as:

  * Page visits and duration
  * Bounce rates and exit rates
  * Traffic source and visitor type


## 🛠 Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn
* Jupyter Notebook


## 📈 Analysis Performed

### 1. Exploratory Data Analysis (EDA)

* Examined user behaviour patterns across sessions
* Identified key variables influencing purchase decisions
* Analysed distributions of categorical and numerical features
* Observed class imbalance (majority non-purchasing users)


### 2. Feature Analysis

* Investigated relationships between session features and revenue
* Identified important predictors such as:

  * Page value
  * Exit rate
  * Time spent on product-related pages


### 3. Machine Learning Model

* Built a classification model to predict purchase intention
* Evaluated model performance using standard metrics
* Addressed class imbalance in the dataset


## 📓 Notebook

👉 `ecommerce_revenue_prediction.ipynb`


## 🚀 Project Highlights

* Performed end-to-end data analysis (EDA → modeling)
* Identified behavioural drivers of customer purchases
* Built a predictive model for revenue generation
* Demonstrated practical application of machine learning in e-commerce


## 📌 Key Takeaways

* User behaviour metrics are strong indicators of purchase intent
* Time spent and engagement significantly influence conversions
* Machine learning can support decision-making in online retail


## 📁 Repository Structure

```bash
├── ecommerce_revenue_prediction.ipynb
├── data/
│   └── online_shoppers_intention.csv
├── README.md
```

## 📎 Notes

* Dataset included for reproducibility
* This project demonstrates both **data analysis** and **machine learning skills**
