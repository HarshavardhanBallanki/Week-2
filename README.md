# 🌍 Carbon Emissions Prediction using Socioeconomic and Environmental Indicators

This project was developed as part of the **Shell AICTE Virtual Internship in Artificial Intelligence**, facilitated by **Edunet Foundation**. It focuses on building a machine learning model to predict **total carbon emissions (CO₂)** based on various environmental, economic, and demographic features.

---

## 📌 Objective

To explore the relationship between **carbon emissions** and multiple influencing factors like energy consumption, population, GDP, urbanization, and mortality rates, and predict total CO₂ emissions using machine learning.

---

## 🗂️ Project Structure

carbon-emissions-prediction/
├── climate_change_download_0.xls         # Raw dataset from World Bank
├── 1_Data_preparation.ipynb              # Data loading, transformation, cleaning
├── 2_data_exploration.ipynb              # Exploratory Data Analysis (EDA)
├── data_cleaned.csv                      # Cleaned dataset used for modeling
├── README.md                             # Project overview and documentation

## 📊 Dataset Overview

Source: Climate-related indicators (e.g., energy use, urban population, GDP) from the World Bank.

Total Records: 1700

Features: 18

Key Columns:

co2_ttl: Total CO₂ emissions (target variable)

en_per_cap: Energy use per capita

gdp, gni_per_cap: Economic indicators

pop, urb_pop, pop_growth_perc: Demographic indicators

prot_area_perc: Protected areas as % of land area

## 🔍 Key Steps

## 🧹 1. Data Preparation
Parsed .xls World Bank dataset

Cleaned and merged multiple indicators by country and year

Created a unified data_cleaned.csv file

## 📈 2. Exploratory Data Analysis
Correlation heatmaps to find important predictors of CO₂

Trend analysis of emissions across years and countries

Detection of multicollinearity and scaling of features

## 🔮 3. Model Building (Future Scope)
This project sets the foundation for future predictive modeling using regression techniques such as:

Linear Regression

Random Forest Regressor

XGBoost

## 🧠 Tools & Technologies
Python, Jupyter Notebook

Pandas, NumPy – Data handling

Matplotlib, Seaborn – Visualizations

Scikit-learn (for next phase) – ML models

## 📌 Learnings & Outcome

Gained insights into how economic and demographic factors contribute to carbon emissions.

Understood the challenges of working with multi-indicator global datasets.

Prepared a clean dataset for future training of ML models to predict CO₂ emissions with high accuracy.

## 📈 Next Steps

Implement regression models to predict co2_ttl.

Evaluate model performance using R², RMSE, MAE.

Build a web-based dashboard using Streamlit for interactive visualization and prediction.

## 🙏 Acknowledgements

Special thanks to:

Shell, AICTE, Edunet Foundation, and IBM SkillsBuild

The mentors and coordinators for guidance and learning materials

## 🤝 Connect with Me

LinkedIn • GitHub • Email
