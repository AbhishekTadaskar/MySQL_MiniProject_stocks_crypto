# 📊 SQL Mini Project: Stocks & Cryptocurrency Analysis  

## 📌 Project Overview  
This mini-project demonstrates the use of **SQL queries** for performing analysis on two datasets:  

- **Stocks Dataset** (`stocks.csv`)  
- **Cryptocurrency Dataset** (`cryptocurrency.csv`)  

The project covers **beginner, intermediate, and advanced SQL queries**, including:  
- Basic data selection  
- Aggregation functions  
- Joins and subqueries  
- Window functions (ranking)  
- Conditional filtering  
- Real-world case studies (Stock vs Bitcoin daily average, Market cap analysis, etc.)  

The goal of this project is to **practice SQL queries** on real datasets and strengthen database querying skills.  

---

## 📂 Project Structure  

---

## 🗂 Datasets  

### 1️⃣ Stocks Dataset (`stocks.csv`)  
| Column       | Description |
|--------------|-------------|
| timestamp    | Date & time of record |
| name         | Stock name (e.g., Microsoft, Apple) |
| last         | Last traded price |
| high         | Highest price |
| low          | Lowest price |
| chg_         | Change in price (numeric) |
| chg_%        | Percentage change |
| vol_         | Volume of stock traded |
| time         | Recorded time |

---

### 2️⃣ Cryptocurrency Dataset (`cryptocurrency.csv`)  
| Column       | Description |
|--------------|-------------|
| timestamp    | Date & time of record |
| name         | Cryptocurrency name (e.g., Bitcoin, Ethereum) |
| symbol       | Crypto symbol (BTC, ETH, etc.) |
| price_usd    | Price in USD |
| vol_24h      | 24-hour trading volume |
| total_vol    | Total trading volume |
| chg_24h      | 24-hour percentage change |
| chg_7d       | 7-day percentage change |
| market_cap   | Market capitalization |

---

## ⚡ SQL Queries Included  

The `queries.sql` file includes **20+ SQL queries** categorized as:  

### 🔹 Beginner Level  
1. Find the name and last price of all stocks.  
2. List the name and price_usd for all cryptocurrencies.  
3. Get stocks where the change is positive.  
4. Count total cryptocurrency records.  
5. Average stock last price.  
6. Highest price among cryptocurrencies.  
7. Total market cap of cryptocurrencies.  
8. Average stock price by company.  
9. Lowest stock price.  
10. Stock with highest price per timestamp.  

---

### 🔹 Intermediate Level  
11. Average last price for each stock with more than 5 entries.  
12. Cryptos with higher than average 24h change.  
13. Join stocks & cryptos by timestamp.  
14. Compare Microsoft’s avg stock vs Bitcoin’s avg price.  
15. Stock with largest high-low difference.  
16. Top 3 stocks by price change.  
17. Price difference from overall stock average.  
18. Cryptos with `chg_7d > 1%` and `chg_24h < 0%`.  

---

### 🔹 Advanced Level  
19. For each stock, find crypto with highest market cap on the same date.  
20. Count how many cryptos were recorded on the same date as each stock.  
21. Daily average of Microsoft vs Bitcoin side-by-side.  
22. Ranking stocks by percentage change using `RANK()` (Window Function).  

---







