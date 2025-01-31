# EDA-on-Stock-Price-of-Company
This EDA on Tesla stock prices (2020-2024) analyzes trends, volatility, and patterns using statistical insights and visualizations. It explores price fluctuations, moving averages, and correlations, offering a data-driven understanding of Tesla’s market behavior for investment decisions and future forecasting.
Exploratory Data Analysis (EDA) on Tesla Stock Prices (2020-2024)
Project Overview
This project focuses on Exploratory Data Analysis (EDA) of Tesla Inc. (TSLA) stock price data from January 2020 to January 2024 using advanced data visualization and statistical techniques. The objective is to uncover market trends, volatility, price fluctuations, and key insights that can help understand the stock's behavior over time.

Objectives of the Analysis
Analyze Stock Price Trends – Understanding the variations in opening, closing, high, and low prices.
Detect Market Volatility – Identifying periods of high fluctuations and price swings.
Time Series Analysis – Observing long-term patterns, seasonality, and trend reversals.
Descriptive Statistics & Distribution Analysis – Examining mean, median, standard deviation, and skewness.
Correlation Analysis – Understanding relationships between different stock price components.
Moving Averages & Technical Indicators – Identifying short-term and long-term trends using statistical measures.
Data Collection & Preprocessing
The dataset was obtained from Yahoo Finance API, containing essential attributes such as:

Date – The trading date.
Open Price – The price at the beginning of the trading session.
Close Price – The final price at the end of the trading session.
High Price – The highest value of the stock during the day.
Low Price – The lowest value of the stock during the day.
Volume – The total number of shares traded on that day.
Data Cleaning & Transformation
Handling Missing Data: Any missing or NaN values were checked and imputed using forward-fill/backfill techniques.
Data Type Conversion: The Date column was converted into a datetime format for time-series analysis.
Resampling & Aggregation: Data was resampled into weekly, monthly, and yearly intervals to capture broader trends.
Key Insights & Analysis
1️⃣ Stock Price Trends Over Time
A time-series analysis of Tesla’s opening and closing prices from 2020 to 2024 reveals significant volatility. The stock witnessed a sharp rise in 2021, coinciding with Tesla’s increasing market valuation and financial performance. A notable dip in 2022 can be attributed to external market conditions, including interest rate hikes and economic slowdowns.

2️⃣ Yearly High Prices & Peak Analysis
By analyzing the highest stock prices recorded each year, we observed that:

2021 marked Tesla’s highest stock price surge, reflecting a strong bullish trend.
The 2022-2023 period showed fluctuations, indicating a mix of investor confidence and external economic factors.
The 2024 trend shows signs of recovery and stabilization.
3️⃣ Market Volatility & Price Fluctuations
The dataset exhibits high volatility, especially during key economic and company-specific events:

Q4 2020 - Q1 2021: A rapid price surge due to increased investor interest and strong financial performance.
2022: A period of price corrections and high fluctuations due to macroeconomic concerns.
2023-2024: A stabilization phase with steady growth.
4️⃣ Moving Averages & Trend Reversals
By applying 50-day and 200-day moving averages, we identified:

Short-term fluctuations that indicate investor sentiment shifts.
Long-term trends that reflect broader market performance and potential investment opportunities.
Crossovers between moving averages, signaling potential trend reversals.
5️⃣ Stock Price Correlation Analysis
Open vs. Close Prices: A strong positive correlation indicates Tesla’s price movements follow a predictable pattern.
High vs. Low Prices: A wide price range suggests active intraday trading and high market activity.
Volume vs. Price Movement: Higher trading volumes often align with increased price volatility.
