# E-Commerce Consumer Behavior Analysis

## Objective
Analyze customer purchasing patterns, product performance, and country-level sales trends in an e-commerce dataset to understand key factors driving revenue.

## Tools and Libraries
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## Key Steps
1. Data loading and cleaning (handled duplicates, missing values, and incorrect data types).  
2. Feature engineering – created `TotalRevenue` as `Quantity × UnitPrice`.  
3. Exploratory Data Analysis (EDA): revenue distribution across countries and products, correlation analysis, and time-based revenue trends.  
4. Derived business insights from visual patterns and data relationships.

## Insights
- The United Kingdom generated the highest number of transactions and total revenue.  
- A few high-performing products account for a large portion of total sales.  
- Revenue spikes show seasonality, with clear holiday-period peaks.  
- Quantity and Unit Price positively correlate with total revenue.

## Project Structure
ECommerce_Consumer_Behavior_Analysis/
├── data/
│ └── data.csv
├── notebooks/
│ └── ECommerce_Analysis.ipynb
├── images/
├── requirements.txt
└── README.md


## Notebook
Open the analysis notebook at `notebooks/ECommerce_Analysis.ipynb` to see complete code, visualizations, and the step-by-step analysis.

## Next Steps
- Customer segmentation using clustering  
- Sales forecasting / time-series modelling

