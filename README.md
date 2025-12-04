# 🚀 PowerBI Crypto Dashboard  
### Comprehensive Cryptocurrency Market Analysis with Python & Power BI  
Created by **Salar Rahnama** (ID: 40131850)

---

## 📌 Overview  
This project provides a full **end-to-end crypto market analytics pipeline**, combining  
**Python preprocessing**, **Power BI visualization**, and **DAX-based analysis**.

It includes:  
- Cleaned multi-currency dataset  
- Multi-page interactive Power BI dashboard  
- Time-series analysis, volatility modeling, and volume-price relationships  
- Custom DAX measures (Monthly Return, Volatility, Avg Close, KPIs)  
- Professional visualization theme & conditional formatting  
- PDF report with full academic documentation  

---

## 📊 Dashboard Features  
### **1. Overview Page**
- Total Market Cap  
- Average Volume  
- Average Close  
- Top 5 Gainers & Top 5 Losers  
- Date & Currency slicers  

### **2. Price Trends Page**
- Daily Close price trends  
- Monthly Return % (DAX)  
- Multi-currency timeline segmentation  

### **3. Comparison Page**
- Avg Close by currency  
- Total & Avg Volume  
- Total Market Cap comparison  
- Liquidity & valuation patterns  

### **4. Insights Page**
- Volume vs Price scatter plot  
- Combined line + bar chart (Average Close + Volume Count)  
- Volatility ranking (% High–Low over Open)  

---

## 🧠 Core Methodology  
### **Data Preprocessing (Python / Jupyter Notebook)**
- Removed NULLs  
- Cleaned numeric fields (removed commas, type conversion)  
- Converted dates to standardized datetime  
- Sorted by currency and date  
- Added `year`, `month`, and `YearMonth` for time-based DAX  
- Produced: `cleaned_coin_data.csv`

### **Power BI Modeling**
- Imported cleaned dataset  
- Built relationships & hierarchies  
- Created DAX measures:
  - `Avg_Close`
  - `Monthly Close`
  - `PreviousMonthClose`
  - `Monthly_Return`
  - `Volatility`

### **Advanced Enhancements**
- Applied professional theme  
- Added conditional formatting (Top/Bottom 5 Returns)  
- Attempted API integration for Fear & Greed Index  
  - Error documented regarding malformed JSON response  

---

