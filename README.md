# Financial Performance Analytics & Revenue Forecast (Python)

A Python project that analyzes monthly revenue, cost and profit margin, and forecasts revenue for the next 12 months using a linear trend model.

## Project Screenshots
![Screenshot 1](Screenshot%202026-11-17%20110806%20-%20Copy%20-%20Copy.png)

![Screenshot 2](Screenshot%202026-11-17%20115341.png)

![Screenshot 3](Screenshot%202026-11-17%20115657.png)

## Objective
Track revenue and profitability over 3 years (2022 to 2024) and estimate where revenue is heading over the next 12 months.

## Tools Used
- Python
- Pandas and NumPy
- Matplotlib
- Jupyter Notebook

## Method
- Cleaned and summarized monthly financial data with Pandas
- Built a four-chart dashboard: monthly revenue trend with a 3-month average, yearly revenue, cost and profit, monthly profit margin, and monthly revenue growth
- Fitted a straight-line trend with `np.polyfit` and used it to forecast the next 12 months

## Key Insights
- Revenue grew from about 100k to 180k per month over 3 years, a steady upward trend
- Profit margin swings between 28% and 40%, so costs are not stable from month to month
- The linear forecast predicts 16% growth (2.07M to 2.40M) over the next 12 months
- The forecast is a straight line, so it ignores seasonality and sudden changes
- Next step: test other forecasting methods, such as moving averages or Prophet

## Author
**Heena Kausar**

- GitHub: [hkausar542-cyber](https://github.com/hkausar542-cyber)
- LinkedIn: [Heena Kausar](https://www.linkedin.com/in/heena-kausar-256331301/)
