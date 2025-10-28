 # 📊 TCS Stock Analysis Dashboard — Power BI Project

## 🔰 Overview
This project presents a **comprehensive Power BI dashboard** analyzing the stock performance of **Tata Consultancy Services (TCS)**.  
It visualizes daily and quarterly trends, stock price fluctuations, and trading volume patterns to provide **data-driven insights** into TCS’s market behavior.

---

## 🧩 Dataset Details
**Dataset Name:** `TCS_NS.csv`  
**Source:** Yahoo Finance / Kaggle (TCS Stock Data)  
**Columns Used:**
- 📅 Date  
- 💹 Tata Open  
- 📈 Tata High  
- 📉 Tata Low  
- 🔒 Tata Close  
- 🔁 Tata Adj Close  
- 📊 Tata Volume  

---

## ⚙️ Data Preparation
Data cleaning and transformation were performed using **Power Query** in Power BI:
- Converted `Date` to **Date/Time** format  
- Created new calculated columns:
  - **Year** → `Year = YEAR([Date])`
  - **Month** → `Month = FORMAT([Date], "MMMM")`
  - **Quarter** → `Quarter = "Q" & FORMAT(ROUNDUP(MONTH([Date])/3,0), "0")`
  - **Day** → `Day = FORMAT([Date], "DD")`
- Removed null values and formatted numerical fields.

---

## 📈 Dashboard Highlights
### 🟢 **1. KPI Metrics**
| Metric | Value |
|:------|:------:|
| Average Open | ₹3,280 |
| Average Close | ₹3,285 |
| Average High | ₹3,320 |
| Average Low | ₹3,250 |
| Average Volume | 1.6M Shares |

---

### 🟣 **2. Visuals Included**
- **Line Chart:** Month-wise stock trend (Open, High, Low, Close)
- **Bar Chart:** Volume comparison over time
- **Cards:** Key performance indicators (Open, Close, High, Low)
- **Slicers:** Year, Month, and Quarter filters for dynamic insights
- **TCS Logo:** For a professional and branded dashboard appearance

---

## 🔍 Key Insights
✅ **Positive Growth:** Average close slightly higher than open → steady upward trend.  
✅ **Moderate Volatility:** Price fluctuates ₹70–₹100 daily on average.  
✅ **Volume Spikes:** Observed near dips — investor accumulation behavior.  
✅ **Quarterly Trend:** Q1 shows strong performance, Q2 minor decline, Q3–Q4 steady recovery.  
✅ **Investment Signal:** Consistent stability makes TCS a reliable long-term holding.

---

## 🖼️ Dashboard Preview

### 📊 **Dataset Preview**
![Dataset Preview](Tcs/PREVIEW/DATASETPREVIEW)

---

### 📸 **Overall Dashboard View**
![Overall Dashboard](Tcs/PREVIEW/OverallDashboard)
![Overall Dashboard 2](Tcs/PREVIEW/OverallDashboard2)

---

### 🧭 **Trend by Year**
![Trend by Year](Tcs/PREVIEW/TRENDBYYEAR)

---

### 📈 **Quarterly Analysis**
![Quarterly Analysis](Tcs/PREVIEW/QuarterlyAnalysis)

---

### 💡 **Insights Dashboard**
![Insights](Tcs/PREVIEW/insights)
![Insights 2](Tcs/PREVIEW/insights2)

---

## 🧠 Tools & Technologies
- **Power BI** – Data Visualization  
- **Microsoft Excel** – Data Source & Preprocessing  
- **DAX & Power Query** – Calculations and Transformations  
- **GitHub** – Version Control and Project Showcase  

---

## 🏁 Conclusion
This Power BI project provides a **clear visual narrative of TCS’s stock movement** — helping analysts and investors identify trends, volatility, and opportunities in a simple yet powerful interface.

> _“Turning data into insights — The Power of BI meets the Power of TCS.”_

---

## 📬 Author
👨‍💻 **Anmol Pandey**  
🎓 BCA Student | Data Analyst Enthusiast | Power BI Developer  
📍 Lovely Professional University  
🔗 [LinkedIn](https://www.linkedin.com/in/) | [GitHub](https://github.com/)  

---

### ⭐ Don’t forget to star this repository if you found it useful!
