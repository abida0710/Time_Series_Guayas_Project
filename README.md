# Time Series Forecasting Project - Guayas Region

## 📌 Project Objective
The main goal of this project is to forecast unit sales for retail stores located in the Guayas region using time series data. The analysis focuses on cleaning, exploring, and preparing the data for machine learning modeling.

## 🛠️ Steps Completed
- **Data Cleaning**:  
  - Filled missing promotions with `False`.
  - Forward filled missing oil prices and backward filled when needed.
  - Handled missing dates by filling zero unit sales.
  - Detected and handled outliers in `unit_sales` using Z-score method.

- **Feature Engineering**:
  - Created date-related features: year, month, day of week, weekend.
  - Built lag features: previous day sales, 7-day lag sales.
  - Computed rolling statistics: 7-day and 30-day moving averages.
  - Integrated oil price as an external feature.

- **Exploratory Data Analysis (EDA)**:
  - Visualized overall sales trends over time.
  - Analyzed weekly and monthly sales seasonality.
  - Examined the influence of promotions and oil prices on sales.
  - Investigated sales distribution and variability.
  - Focused specifically on the Guayas region for deeper insights.

## 🔍 Key Findings
- Sales show strong weekly patterns, with weekends typically higher.
- December shows a consistent spike in sales (holiday season effect).
- Oil prices show minor correlation with unit sales.
- The dataset is now fully cleaned, structured, and ready for modeling.

## 📂 Files
- `Time_Series_Project_Guayas_Region.ipynb` - Full Colab Notebook with data cleaning, EDA, and feature engineering.
- `cleaned_guayas_dataset.csv` - Final prepared dataset for modeling.

 

