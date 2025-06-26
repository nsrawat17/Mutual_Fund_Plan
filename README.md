# Mutual_Fund_Plan
Mutual Fund Plan with Python
🧠 Project Objective
This project demonstrates how to create a Mutual Fund Plan using Python. It involves analyzing historical stock market data (specifically from NIFTY 50 stocks), calculating return on investment (ROI), managing risk through volatility analysis, and estimating the future value of monthly investments.

🚀 Project Workflow
The mutual fund plan is developed through the following steps:

Gather Historical Stock Data
Load closing prices and trends of NIFTY 50 stocks over time.

Analyze Stocks
Calculate essential metrics like Return on Investment (ROI) and Volatility to evaluate stock performance.

Select Stocks
Filter stocks that have high returns with low volatility to balance risk and reward.

Forecast Investment
Use a compound interest formula to estimate the future value of monthly investments in selected stocks.

📊 Dataset Used
File: nifty50_closing_prices.csv

Content: Daily closing prices of NIFTY 50 stocks

Source: NSE India or similar market data APIs

🧮 Features / Analysis Performed
Data Cleaning and Formatting (Date, Close prices)

ROI Calculation:

𝑅𝑂𝐼=(Final Price−Initial Price/Initial Price)×100

Volatility Measurement (Standard Deviation of returns)

Future Value Forecast:

𝐹𝑉=𝑃×((1+𝑟/𝑛)^𝑛⋅𝑡−1/(𝑟/𝑛)×(1+𝑟/𝑛)
where:

P = Monthly investment

r = Annual return rate

n = Compounding frequency

t = Time in years

📈 Visualization
Line charts showing stock trends

ROI and Volatility comparisons

Future Value projections over multiple time frames

🛠️ Technologies Used
Python 3

Jupyter Notebook

NumPy, Pandas, Matplotlib, Seaborn
jupyter notebook Mutual_Fund_Plan.ipynb

🔮 Future Scope
Include real-time stock updates via APIs (e.g., yfinance)
👨‍💻 Author
Naresh Singh Rawat
Aspiring Data Analyst | B.Tech 4th Year
📍 Gurgaon, India
