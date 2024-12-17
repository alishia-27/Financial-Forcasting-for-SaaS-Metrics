# **Financial Forecasting for SaaS Metrics**
### **Overview**
This project forecasts **Annual Recurring Revenue (ARR)**, a key SaaS metric, using **Simple Exponential Smoothing**. The goal is to analyze historical trends and provide actionable revenue projections for the next 12 months.
---
### **Objectives**
1. Clean and process SaaS financial data for ARR analysis.
2. Visualize historical ARR trends.
3. Forecast ARR for the next 12 months.
4. Provide insights for revenue growth and strategy.
---
### **Dataset**
This Dataset can be found in [Kaggle](https://www.kaggle.com/datasets/gjthompson1/tech-company-data-getlatkacom?resource=download). Key columns used:

- `financials.arr_max` and `financials.arr_min`: To calculate average ARR.
- `financials.created_at`: Date of recorded metrics.
---
### **Tools**
- **Python**: `Pandas`, `Matplotlib`, `Statsmodels`
---
### **Steps**
1. **Data Preparation**: Cleaned and resampled ARR data monthly.
2. **Visualization**: Plotted historical ARR trends.
3. **Forecasting**: Applied Simple Exponential Smoothing for 12-month ARR predictions.
---
### **Results**
- Clear 12-month ARR forecast.
- Insights into ARR growth patterns to inform decision-making.
---
### **To Run the Project**
1. Clone the repo: ```bash git clone https://github.com/your-username/financial_forecasting.git``` cd financial_forecasting
2. Run the script: ```bash python arr_forecasting.py```
3. Output: Forecast saved as `arr_forecast.csv.`
---
### **Future Work**
- Add churn analysis and advanced forecasting models.
- Build interactive dashboards with Tableau or Power BI.
---
### **Author:** [Alishia D’Souza](https://www.linkedin.com/in/AlishiaD-Souza/)
