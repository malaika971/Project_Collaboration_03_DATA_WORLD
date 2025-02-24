# Credit Card Spend Analysis & Forecasting
This project provides a comprehensive analysis pipeline that examines historical credit card transaction trends, predicts spending patterns, and detects potential anomalies. The interactive dashboard is built using Streamlit and Plotly, with forecasting handled by Facebook Prophet and customer segmentation via clustering techniques.

# Key Highlights
## Data Preprocessing & EDA:

- Cleaned and standardized raw transaction data.
- Visualized spending trends on daily, monthly, and weekly levels.
- Analyzed seasonal patterns and correlations (e.g., spending vs. city population).
Interactive Dashboard:
- User-friendly input panel to filter by Customer ID, Spending Category, and Time Range.

## Dynamic, interactive visualizations across multiple tabs:
- Spending Trends: Daily, Monthly, Weekly, and Seasonal spending patterns.
- Spending Behavior Analysis: Boxplots, spending behavior before/after payday, high vs. low spenders, and outlier detection.
- Forecasting and Anomalies: Enhanced transaction forecast and anomaly detection.
- Customer Segmentation: Clustering based on spending habits and transaction description clusters.
- Correlation and Distribution: Correlation between spending and city population, plus transaction amount distribution.

## Forecasting & Anomaly Detection:

- Developed models using Facebook Prophet to predict spending trends.
- Identified anomalies that may indicate unusual spending or potential fraud.
- Applied K-Means clustering for effective customer segmentation.

## Tools & Libraries
- Streamlit – For building the interactive dashboard.
- Plotly Express & Plotly Graph Objects – For creating interactive visualizations.
- Facebook Prophet – For time series forecasting.
- Pandas & NumPy – For data manipulation.
- scikit-learn – For clustering and anomaly detection.
