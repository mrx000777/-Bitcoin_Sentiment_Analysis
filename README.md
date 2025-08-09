# 📊 Trader Performance vs. Market Sentiment Analysis

## 📌 Overview
This project explores the relationship between **trader performance** and **market sentiment** (Fear & Greed Index).  
By combining historical trade data with sentiment data, we aim to uncover **hidden patterns** that can help in creating **smarter trading strategies**.

---

## 🗂️ Data Sources
1. **Trader Data** – Includes details such as execution price, trade size, closed PnL, and timestamps.
2. **Market Sentiment Data** – Daily Fear & Greed Index values, classified as:
   - Extreme Fear
   - Fear
   - Neutral
   - Greed
   - Extreme Greed

---

## ⚙️ Steps in the Analysis
1. **Load Data**  
   Read trade history and sentiment index data from CSV files.
   
2. **Clean & Format**  
   - Convert timestamps to proper date format.
   - Map sentiment text to numerical values for analysis.

3. **Merge Datasets**  
   Combine trade and sentiment data based on matching dates.

4. **Exploratory Data Analysis (EDA)**  
   - Summary statistics of Closed PnL grouped by sentiment.
   - Boxplots to visualize distribution of profits in different market moods.

5. **Insights**  
   Identify whether traders tend to perform better in Fear or Greed markets.

---

## 📊 Example Output
- **Performance Summary by Sentiment**
