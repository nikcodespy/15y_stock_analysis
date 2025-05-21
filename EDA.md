## 📊 Exploratory Data Analysis: 15-Year Tech Stock Trends

This document summarises the EDA (Exploratory Data Analysis) I performed using MySQL on historical stock data from 2010 to 2024 for five major tech companies: AAPL, AMZN, GOOGL, MSFT, and NVDA.

## 🔍 What I Did

Using beginner-friendly SQL queries, I explored long-term performance, average closing prices, volatility, and consistency across five major tech stocks. The dataset was cleaned and transformed into a long format with columns for Date, Ticker, Open, High, Low, Close, and Volume.

## ❓ Questions I Answered

** ✅ Q1: Which company delivered the highest return from 2010 to 2024? **

Solved by: Calculating each stock's total return (%) by comparing the first and last available closing prices from 2010 to 2024.

Why: This is a key metric for assessing long-term growth potential and understanding which companies created the most value for investors over time.

![Image](https://github.com/user-attachments/assets/ac074bd8-c553-4b57-9dc2-c6955d778ea6)

Result:
NVDA had the highest return, reflecting a massive growth in the GPU and AI space

![Image](https://github.com/user-attachments/assets/678d711c-a5f1-4f4e-854a-f6ff6c983f06)


** ✅ Q2: Annual average closing price per stock **

Solved by: Computing each stock's yearly average closing price from 2010 to 2024.

Why: This helps identify year-over-year performance trends and growth trajectories, smoothing out daily volatility.

![Image](https://github.com/user-attachments/assets/7ee34165-435d-4339-ab7d-95dadd1ce302)

Result:
These major stocks have a positive growth on average every year due to the innovation & adaptability to current new trends

![Image](https://github.com/user-attachments/assets/58bd4dad-3832-4066-bffd-207fe0f46cc8) ![Image](https://github.com/user-attachments/assets/4db20115-8291-43c8-9f55-046807e4239c) ![Image](https://github.com/user-attachments/assets/ac8f595d-70a2-437c-bbb4-8d16e845a968)


** ✅ Q3: Standard deviation of closing prices (price stability) **

Solved by: Measuring the standard deviation of each stock’s closing prices over the full 15-year period.

Why: This is a measure of price volatility or risk — lower values indicate more stable pricing, which may appeal to risk-averse investors.

![Image](https://github.com/user-attachments/assets/9b60ec54-1476-473e-abbd-cf834008d44a)

Result:
NVDA showed the most stable price behaviour while MSFT showed the highest volatility.

![Image](https://github.com/user-attachments/assets/eb85755b-53b8-4d62-89a6-71fce94b31d1)


** ✅ Q4: Best-performing years by highest average closing price **

Solved by: Identifying the best year per stock by the highest average closing price.

Why: This highlights peak performance years, useful for understanding when a company had maximum market confidence or performance.

![Image](https://github.com/user-attachments/assets/9d6a6d0c-609d-4059-9cc1-2c633000961d)

Result:

Every company has peaked in 2024

![Image](https://github.com/user-attachments/assets/a11f9967-e887-4432-aee7-de43cd89a0af) ![Image](https://github.com/user-attachments/assets/d4a4913e-c801-4bb4-a652-d549c18cb282) ![Image](https://github.com/user-attachments/assets/69d2ac70-db9c-4e55-a0a1-c6e5e44dc6e9)


** ✅ Q5: What was the highest and lowest price each stock ever reached? **

Solved by: Extracting the historical max and min closing prices for each company.

Why: This provides a price range reference to assess risk-reward potential and historical volatility extremes.

![Image](https://github.com/user-attachments/assets/dbe6dcd9-c0e9-4ac8-a29e-1b8e24bb03bb)

Result:

![Image](https://github.com/user-attachments/assets/43010a44-9821-473c-9faa-bfedaac3aef9)


** ✅ Q6: What is the average daily volume per stock? **

Solved by: Calculating the average number of shares traded per day for each company.

Why: Volume reflects market liquidity and investor interest — higher volume suggests better tradability and market confidence.

![Image](https://github.com/user-attachments/assets/0451502a-6976-42fa-a05d-4c95c14260be)

Result:

![Image](https://github.com/user-attachments/assets/2bb7aa83-0eae-486a-88ea-f983a24df8a3)
