# 📈 Investment Strategy Analysis: Sector-Based Portfolio Simulation

## 📌 Project Overview
This project analyzes an **investment strategy** that ranks and invests in **sectoral indices** based on their **annual and semi-annual returns**. The strategy is benchmarked against **Nifty 50** to evaluate performance. The goal is to identify **high-performing sectors** and assess **risk-adjusted returns**.

## 🚀 Key Features
- **Data Preprocessing:** Loads and cleans financial data from multiple sectoral indices.
- **Annual and Semi-Annual Ranking:** Ranks sectors based on their returns every **6 months or 1 year**.
- **Investment Strategy Simulation:** Allocates funds dynamically into **Top, Middle, and Bottom sectors**.
- **Benchmarking Against Nifty 50:** Compares the strategy's performance with **Nifty 50**.
- **Performance Metrics:** Calculates **Sharpe Ratio, Volatility, and Drawdowns**.
- **Data Visualization:** Plots investment growth and risk metrics.

## 📊 Data Sources
The analysis is based on **sectoral index data** for the following **15 sectors**:
- Auto
- Bank
- Consumer Durables
- Energy
- Financial
- FMCG
- Healthcare
- Housing
- IT
- Metal
- Oil & Gas
- Private Bank
- Pharma
- PSU
- Realty

The **Nifty 50 index** is used as a benchmark.

## 📜 Methodology
### **1️⃣ Data Preparation**
- Reads **historical closing prices** from CSV files.
- Converts date columns into **datetime format** and sorts them.

### **2️⃣ Computing Returns**
- Calculates **annual and semi-annual returns** for each sector.
- Ranks sectors based on **performance**.

### **3️⃣ Investment Strategy**
- Divides sectors into **Top 5, Middle 5, and Bottom 5** groups.
- Allocates **$100 to each group** and reinvests returns every cycle.
- Tracks **portfolio growth** over time.

### **4️⃣ Performance Evaluation**
- Plots **investment growth over time**.
- Computes **maximum drawdowns** to assess risk.
- Calculates **Sharpe Ratio & Volatility** for risk-adjusted returns.


