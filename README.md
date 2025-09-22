# ai_in_healthcare03
This project analyzes the COVID-19 global deaths dataset by reshaping it into long format, handling missing values, and converting dates. A SARIMAX model forecasts death trends for selected countries, while Logistic Regression on latitude and longitude predicts high- or low-death regions, combining data cleaning, visualization, and modeling.
# AI in Healthcare – COVID-19 Deaths Analysis

## 📌 Description
This project uses the COVID-19 global deaths dataset from Johns Hopkins CSSE to apply data cleaning, transformation, and predictive modeling. The dataset contains both non-time-series data (location info) and time-series data (daily cumulative deaths).  

## 🚀 Features
- Data preprocessing: handling missing values, converting dates, reshaping to long format  
- Time series forecasting with **SARIMAX**  
- Logistic Regression on **latitude and longitude** to classify high vs low death regions  
- Evaluation with metrics and visualizations (RMSE, ROC curve, etc.)  

## 📂 Dataset
Source: [Johns Hopkins CSSE COVID-19 Data](https://github.com/CSSEGISandData/COVID-19)  

## ⚙️ Installation
Make sure you have Python 3 and install the following packages:
```bash
pip install pandas numpy matplotlib scikit-learn statsmodels
