# Stock Price Analysis Using Python and SQL (AAPL)

## Overview
This project performs an end-to-end analysis of historical Apple (AAPL) stock price data using Python and SQL. The focus is on identifying trends, volatility patterns, and time-based behavior through data cleaning, aggregation, and visualization.

The analysis demonstrates how Python and SQL can be combined to explore financial time series data and extract actionable insights.

## Data Source
Historical stock price data for Apple Inc. (AAPL) was retrieved using the Yahoo Finance API.

The dataset contains daily time-series data, including:
- Open
- High
- Low
- Close
- Adjusted Close
- Trading Volume


---

## Tools & Technologies
- **Python** (Pandas, NumPy)
- **SQL (SQLite)**
- **Matplotlib**
- **Yahoo Finance (yfinance)**
- **Jupyter Notebook**

---

## Methodology
1. **Data Loading**
   - Pulled historical AAPL stock data using the Yahoo Finance API.

2. **Data Inspection**
   - Examined data structure, types, and summary statistics.
   - Verified completeness and consistency of records.

3. **Data Cleaning**
   - Converted the date index into a column for SQL compatibility.
   - Flattened and normalized column names to ensure smooth SQL querying.

4. **SQL Table Creation**
   - Stored the cleaned dataset in a SQLite database.
   - Verified schema and record count using SQL queries.

5. **SQL Exploration**
   - Performed aggregation queries such as average closing prices.
   - Validated numeric fields and table structure.

6. **Time-Based Analysis**
   - Computed monthly average closing and adjusted closing prices.
   - Compared trends using SQL and Python.

7. **Visualization**
   - Created line charts to compare monthly Close vs Adjusted Close prices.
   - Clearly labeled axes and legends for interpretability.

---

## Key Insights
- Monthly trends show consistent movement between Close and Adjusted Close prices.
- Adjusted Close accounts for corporate actions and provides a smoother long-term trend.
- SQL-based aggregation integrates effectively with Python-based visualization.

---

- Trading volume analysis highlights periods of increased market activity and complements price-based trends.

---

## Visualizations
- Average Monthly Close vs Adjusted Close Price (AAPL)
- Average Monthly Trading Volume (AAPL)

---

## Conclusion
This project demonstrates the ability to:
- Work with real-world financial data
- Combine Python and SQL in a single analysis pipeline
- Perform time-based aggregation and visualization
- Communicate insights clearly through code and documentation

---

## Next Steps
- Extend the analysis to multiple stocks for comparison
- Analyze trading volume trends
- Calculate and visualize daily or monthly returns
