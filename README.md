# Predictive Analysis of Gun Violence Incidents in the United States

This project applies Python-based predictive analytics techniques to explore and forecast patterns in U.S. gun violence incidents using publicly available data from the Gun Violence Archive. The analysis includes data cleaning, exploratory data analysis, feature engineering, visualization, and the development of two predictive modeling approaches:

- **Linear Regression** for aggregated monthly state-level predictions  
- **ARIMA Time-Series Forecasting** for national daily incident trends  

The project examines how data structure (daily vs. monthly aggregation) affects model performance and identifies which patterns—such as seasonality or geographic variation—contribute most to predicting incident volume.

---

## **Objectives**
- Identify long-term and seasonal trends in national gun violence incident data  
- Compare predictive performance between regression and ARIMA models  
- Evaluate how aggregation level (daily vs. state-monthly) impacts forecast stability  
- Explore practical implications for public safety planning and resource allocation  

---

## **Key Findings**
- Daily incident data is highly volatile, causing simple regression models to underperform  
- ARIMA models provide more reliable short-term forecasting through autocorrelation  
- Monthly state-level aggregation reveals stable geographic and seasonal trends  
- Regression performs significantly better on state-month data due to reduced noise  

---

## **Methods & Tools**
**Python Libraries:**
- Pandas  
- NumPy  
- Matplotlib  
- StatsModels (ARIMA)  
- Scikit-learn (Linear Regression)

**Techniques Used:**
- Data cleaning and preprocessing  
- Feature engineering (year, month, victims, daily and monthly aggregates)  
- Exploratory data analysis  
- Regression modeling  
- Time-series forecasting  

---

## **Dataset**
Public dataset from the Gun Violence Archive (via Kaggle):  
https://www.kaggle.com/datasets/jameslko/gun-violence-data

---

## **Project Structure**
- `notebook.ipynb` – Main analysis and modeling notebook  
- `plots/` – Visualizations generated during the analysis (optional)  
- `README.md` – Project overview and documentation  

---

## **How to Run**
1. Clone the repository  
2. Install required libraries  
3. Open the Jupyter Notebook  
4. Run the notebook sequentially to reproduce results  

---

## **Future Work**
- Incorporating population, socioeconomic, or legislative features  
- Testing Seasonal ARIMA or machine learning forecasting models  
- Extending dataset beyond 2018 for more robust long-term insights  
