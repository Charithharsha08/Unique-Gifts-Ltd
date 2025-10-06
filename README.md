# 🛍️ Unique Gifts Ltd — Strategic Growth Analysis  
### Group Project | ITS 2122: Python for Data Science & AI (Semester 3 – 2025)  

---

## 📘 Overview  

This repository contains the group project for **ITS 2122 – Python for Data Science & AI** at the **Institute of Software Engineering (IJSE)**.  
Our team acted as **data science consultants** for *Unique Gifts Ltd*, a UK-based e-commerce retailer specializing in unique giftware.  

The objective was to apply data-driven analytics and AI concepts to extract strategic business insights from real-world transactional data and deliver a **growth strategy backed by evidence**.

---

## 🎯 Objectives  

We analyzed two years of sales data to answer these core business questions:

1. **Sales Performance & Seasonality** — What are the key sales trends and peak periods?  
2. **Product Portfolio Optimization** — Which products are “bread-and-butter” vs. “cash cows”?  
3. **Geographic Insights** — How do UK and international markets compare?  
4. **Customer Segmentation (RFM)** — How can we group customers by behavior to tailor marketing?  
5. **Wholesale vs Retail Behavior** — How do bulk buyers differ from individual customers?  

---

## 🧠 Key Skills & Concepts Applied  

- **Data Cleaning & Validation** (Pandas / NumPy)  
- **Exploratory Data Analysis (EDA)** and visual storytelling (Matplotlib / Seaborn)  
- **Customer Segmentation Modeling** (RFM Framework)  
- **API Integration** for currency conversion (Requests library)  
- **Data driven strategic recommendations** and professional reporting  

---

## 🧩 Dataset Overview  

**Dataset:** *Online Retail II* — UCI Machine Learning Repository  
[Online Retail II Dataset](https://archive.ics.uci.edu/dataset/502/online+retail+ii)  

| Column | Description |
|--------|--------------|
| Invoice | Unique transaction ID (prefix "C" = cancellation) |
| StockCode | Product identifier |
| Description | Product name |
| Quantity | Units per transaction |
| InvoiceDate | Transaction date & time |
| Price | Unit price (£) |
| CustomerID | Unique customer identifier |
| Country | Customer location |

---

## ⚙️ Tech Stack  

| Category | Tools / Libraries |
|-----------|------------------|
| **Language** | Python 3.11 + |
| **Data Processing** | pandas, numpy |
| **Visualization** | matplotlib, seaborn |
| **API Integration** | requests |
| **IDE / Environment** | Jupyter Notebook, VS Code, Google Colab |

---

## 📊 Project Phases  

### **Phase 1 – Data Sanitation & Preprocessing**  
- Removed duplicates, null CustomerIDs, and canceled orders.  
- Created new features (`TotalPrice`, `Year`, `Month`, `DayOfWeek`, `HourOfDay`).  

### **Phase 2 – Exploratory Data Analysis (EDA)**  
- **Temporal Trends:** Monthly and weekly sales patterns.  
- **Geographic Insights:** Top countries by revenue and UK vs. global market split.  
- **Product Portfolio:** Top 10 by quantity vs. revenue comparison.  

### **Phase 3 – Customer Segmentation (RFM Model)**  
- Calculated Recency, Frequency, and Monetary scores.  
- Classified customers into segments (Champions, Loyal, At-Risk, etc.).  

### **Phase 4 – Strategic Insights (Wholesaler Hypothesis)**  
- Identified distinct wholesale vs. retail customer patterns via spend distribution analysis.  

### **Phase 5 – API Integration & Data Enrichment**  
- Integrated currency conversion API to convert GBP to USD / EUR for top transactions.  

---

## 🧮 Deliverables  

| Deliverable | Description |
|--------------|-------------|
| **Strategic Insights Report (PDF)** | 2,500–3,000 word business report with findings & recommendations |
| **Jupyter Notebook (Technical Appendix)** | Clean, reproducible analysis code and visuals |
| **Presentation Slides** | 30-minute boardroom presentation + Q&A session (5 members x ~6 mins each):contentReference[oaicite:2]{index=2} |

---

## 🧾 Evaluation Criteria  

| Component | Weight |
|------------|--------|
| Strategic Report | 50 % |
| Jupyter Notebook | 40 % |
| Teamwork & Presentation Viva | 10 % |

> Grading is based on code quality, data accuracy, analytical depth, visual storytelling, and professional communication:contentReference[oaicite:3]{index=3}.

---

## 👥 Team Members & Roles  

| Member | Role | GitHub |
|--------|------|--------|
| **Charith Harsha** | *Presenter 1 – Data Cleaning & Introduction Lead* | [@Charithharsha08](https://github.com/Charithharsha08) |
| **Tharaka U.G.** | *Presenter 2 – Sales & Market Analysis (EDA)* | [@tharakaug](https://github.com/tharakaug) |
| **Chanuka C.S.J.** | *Presenter 3 – Product Portfolio Analysis* | [@chanukacsj](https://github.com/chanukacsj) |
| **Danitha H.K.** | *Presenter 4 – Customer Analytics (RFM Segmentation)* | [@DanithaHk](https://github.com/DanithaHk) |
| **Vinil Vidushanka** | *Presenter 5 – Strategic Insights & Data Enrichment (API Integration)* | [@vinilvidushanka](https://github.com/vinilvidushanka) |

---

## 🧑‍🏫 Presentation Structure (Per IJSE Guidelines)  

| Section | Presenter | Duration | Key Focus |
|----------|------------|-----------|-----------|
| 1️⃣ Introduction & Data Foundation | Charith Harsha | 5 min | Project overview & data cleaning |
| 2️⃣ Sales & Market Analysis (EDA) | Tharaka U.G. | 7 min | Temporal & geographic trends |
| 3️⃣ Product Portfolio Insights | Chanuka C.S.J. | 5 min | Best-selling vs. high-revenue products |
| 4️⃣ Customer Segmentation (RFM) | Danitha H.K. | 5 min | Customer segments & insights |
| 5️⃣ Strategic Insights & Data Enrichment | Vinil Vidushanka | 8 min | Wholesaler hypothesis & API results + recommendations |

---

## 📬 Contact  

- **Group Lead:** Charith Harsha  
- **Website / Portfolio:** [www.charithharsha.com](https://www.charithharsha.com)  
- **Email:** [harshajayashan@outlook.com](mailto:harshajayashan@outlook.com)

---

## 📄 License  

This project is created for **academic purposes** under the **IJSE Python for Data Science & AI** curriculum.  
Dataset © UCI Machine Learning Repository | Analysis & visuals © 2025 Unique Gifts Ltd Team.  

---
