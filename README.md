# FUTURE_ML_02
Sales Forecasting for Retail Business

📌 1. Importing Libraries
The notebook starts by importing a broad set of libraries:

Data Handling: pandas, numpy

Visualization: matplotlib, seaborn, autocorrelation_plot

Date Utilities: datetime, timedelta

Statistical Modeling: statsmodels, ARIMA, ExponentialSmoothing

Machine Learning: RandomForestRegressor, LinearRegression

Time Series: adfuller, acf, pacf, seasonal_decompose, auto_arima

📂 2. Loading Datasets
Three CSV files are loaded:

stores.csv → store-level info (e.g. store type, size)

train.csv → historical sales data

features.csv → external data (e.g. temperature, fuel price, CPI)

🔗 3. Merging DataFrames and exploring dataset

🧼 4. Data Cleaning

➤ Handling Negative or Zero Weekly Sales

🎉 5. Holiday Analysis

Similar for 
Labor Day
Thanksgiving
Christmas and visualization using sns.barplot

🏪 6. Store Type Analysis
Three store types: A, B, C

Finally,
Time series decomposition, autocorrelation, and forecasting models like ARIMA and ML-based regressors.
