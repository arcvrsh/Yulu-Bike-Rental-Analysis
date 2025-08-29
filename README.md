# Yulu Bike Rental Analysis 🚲📊

This repository contains an end-to-end analysis of **Yulu Bike Sharing** dataset.  
The goal is to explore rental patterns, understand key factors affecting demand, and derive business recommendations through **EDA, Hypothesis Testing, and Statistical Analysis**.

---
## Problem
The company wants to know:

- Which variables are significant in predicting the demand for shared electric cycles in the Indian market?
- How well those variables describe the electric cycle demands

## 📌 Features
- Data cleaning & preprocessing
- Exploratory Data Analysis (EDA)
- Hypothesis testing (ANOVA, Kruskal, T-test, Chi-Square, Correlation)
- Visualizations (Matplotlib, Seaborn)
- Business insights and recommendations

---


## ⚙️ Installation
Clone the repository:
```bash
git clone https://github.com/your-username/yulu-bike-rental-analysis.git
cd yulu-bike-rental-analysis

## install dependencies

pip install -r requirements.txt

jupyter notebook notebooks/yulu_analysis.ipynb

```
## 📊 Key Insights

- Weather & Season strongly affect rentals

- Clear weather and Fall/Summer seasons show the highest demand

- Temperature (20–30°C) is the sweet spot for maximum rentals

- Wind speed negatively impacts demand above 21 kmph

- Working vs Non-Working Days: Registered users prefer weekdays, casual users prefer weekends

- Holiday impact is negligible


## Business Recommendations

- Run promotions during clear weather, especially in fall when demand peaks.

- Adjust inventory or offer incentives during low-demand rainy/snowy days.

- Launch special campaigns for misty weather conditions.

- Offer seasonal promotions in spring and winter to boost demand.

- Target new customer acquisition specifically in spring.

- Apply dynamic pricing, charging more in 20–30°C and discounts in cooler temperatures.

- Monitor wind speeds and warn or incentivize users when winds exceed 21 kmph.

- Encourage rentals during low wind speed periods with offers.


## 🛠️ Tech Stack

- Python (Pandas, NumPy, SciPy, Statsmodels)

- Visualization: Matplotlib, Seaborn

- Jupyter Notebook


![Python](https://img.shields.io/badge/Python-3.11-blue)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)
![License](https://img.shields.io/badge/License-MIT-green)
