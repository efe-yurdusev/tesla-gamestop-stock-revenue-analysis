# Tesla and GameStop Stock & Revenue Analysis

This project explores the relationship between quarterly business revenue and stock price performance for Tesla (TSLA) and GameStop (GME) using Python.

By combining financial market data with company revenue data, this analysis compares whether stock prices move in line with actual business growth.

---

## Project Objectives

- Collect historical stock price data using `yfinance`
- Extract quarterly revenue data through web scraping
- Clean and preprocess raw financial data
- Convert daily stock prices into quarterly average stock prices
- Compare quarterly stock price trends with quarterly revenue
- Measure the correlation between company revenue and stock price

---

## Technologies Used

- Python
- Pandas
- yfinance
- Requests
- BeautifulSoup
- Plotly

---

## Project Workflow

### 1. Data Collection
- Tesla and GameStop stock price history collected via Yahoo Finance API (`yfinance`)
- Revenue data collected from Macrotrends / IBM data source using web scraping

### 2. Data Cleaning
- Removed symbols like `$` and `,`
- Converted revenue values to numeric format
- Converted date columns to datetime
- Filtered data from 2020 onward for consistency

### 3. Data Transformation
- Converted stock data into quarterly average prices
- Matched stock and revenue data by quarter

### 4. Visualization
- Quarterly stock price trend charts
- Quarterly revenue bar charts
- Revenue vs Stock Price scatter plots with trendlines

### 5. Correlation Analysis
- Tesla Correlation: **0.895**
- GameStop Correlation: **0.052**

---

## Key Findings

### Tesla (TSLA)
Tesla showed a strong positive correlation between revenue and stock price.

**Interpretation:**  
As Tesla’s revenue increased, its stock price generally increased as well, suggesting that investor behavior was more closely aligned with business fundamentals.

---

### GameStop (GME)
GameStop showed almost no meaningful correlation between revenue and stock price.

**Interpretation:**  
GameStop’s stock movements were likely influenced more by speculative market behavior and external sentiment rather than direct revenue performance.

---

## Conclusion

This analysis demonstrates that stock prices do not always reflect business fundamentals equally.

- **Tesla:** Revenue growth strongly aligned with stock price growth  
- **GameStop:** Stock price behavior was largely disconnected from revenue trends  

This project highlights the difference between fundamentally driven market performance and sentiment-driven volatility.

---

## Skills Demonstrated

- Financial Data Analysis  
- Web Scraping  
- Data Cleaning  
- Exploratory Data Analysis (EDA)  
- Correlation Analysis  
- Data Visualization  
- Python for Real-World Business Analysis  

---

## Future Improvements

- Add profitability metrics (Net Income, EPS)
- Compare more companies
- Build predictive regression models
- Create dashboard versions

---

## Author

**Hayati Efe Yurdusev**  
Statistics Student | Python | Data Analysis | Aspiring Data Scientist
