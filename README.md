# 📊 E-Commerce Funnel Analysis & Conversion Dashboard

## 📌 Project Overview
This project analyzes user behavior across an e-commerce purchase funnel to identify drop-off points, evaluate marketing channel performance, and uncover opportunities to improve conversion rates.

Using **Python for data analysis** and **Power BI for visualization**, the project tracks how users progress through the funnel stages:

**Browse → Add to Cart → Checkout → Purchase**

The analysis helps answer key business questions such as:

- Where are users dropping off in the funnel?
- Which marketing channels generate the most revenue?
- How do device types influence user behavior?
- What are the overall conversion and drop-off rates?

---

# 🎯 Business Objective
E-commerce companies track user interactions to understand **why users abandon purchases** and how marketing channels influence conversions.

The objective of this project is to:

- Measure **funnel conversion rates**
- Identify **major drop-off points**
- Analyze **channel, device, and regional performance**
- Build an **interactive dashboard for monitoring KPIs**

---

# 📂 Dataset
The dataset contains **21,000+ user interaction events** representing browsing sessions across an online store.

### Key Features

| Column | Description |
|------|-------------|
| User_ID | Unique identifier for each user |
| Session_ID | Session identifier for user visits |
| Event | Funnel stage (Browse, Add to Cart, Checkout, Purchase) |
| Timestamp | Time of user activity |
| Device | Device used (Mobile, Desktop, Tablet) |
| Region | Geographic region |
| Channel | Marketing acquisition channel |
| Product_Category | Product category viewed/purchased |
| Revenue | Purchase value |
| Bounce_Flag | Indicates session bounce |

---

# 🛠 Tools & Technologies

- Python  
- Pandas  
- Matplotlib / Seaborn  
- Power BI  
- Jupyter Notebook  

---

# 🔍 Data Analysis Workflow

### 1️⃣ Data Cleaning
- Converted timestamps to datetime format
- Checked for duplicates and missing values
- Validated event sequence within sessions

### 2️⃣ Feature Engineering
- Created session-level event sequencing
- Aggregated user activity per session
- Generated funnel stage metrics

### 3️⃣ Funnel Analysis

| Stage | Users |
|------|------|
| Browse | 10,000 |
| Add to Cart | 7,059 |
| Checkout | 3,524 |
| Purchase | 1,080 |

---

# 📊 Key Metrics

| Metric | Value |
|------|------|
| Total Users | 10,000 |
| Conversion Rate | **10.8%** |
| Drop-off Rate | **89.2%** |
| Total Revenue | **$1.18M** |

---

# 📉 Funnel Conversion Breakdown

| Funnel Stage | Conversion |
|--------------|------------|
| Browse → Add to Cart | 41.38% |
| Add to Cart → Checkout | 33.30% |
| Checkout → Purchase | 23.46% |

The **Checkout → Purchase stage shows the highest drop-off (~76%)**, indicating a potential friction point in the checkout process.

---

# 📈 Dashboard Features

The Power BI dashboard includes:

- Funnel visualization of user progression
- KPI cards (Users, Conversion Rate, Revenue)
- Revenue breakdown by marketing channel
- User distribution by device
- Revenue by region
- Drop-off rate by device
- Daily revenue trend analysis
- Interactive filters for:
  - Device
  - Channel
  - Region
  - Date

---

# 💡 Key Insights

### 1️⃣ Major Funnel Drop-off
The largest drop occurs at **Checkout → Purchase**, where nearly **76% of users abandon the transaction**.

### 2️⃣ Top Revenue Channels
- **Email:** ~$309K  
- **Google Ads:** ~$305K  

These channels generate the highest revenue.

### 3️⃣ Device Behavior
Drop-off rates are high across all devices:

- Desktop: ~90%
- Mobile: ~89%
- Tablet: ~88%

This suggests checkout issues may not be device-specific.

### 4️⃣ Balanced Regional Performance
Revenue is distributed fairly evenly across regions.

---
# 🚀 Business Recommendations

Based on the analysis:

- Optimize checkout process to reduce abandonment.
- Investigate payment friction or unexpected costs during checkout.
- Increase investment in high-performing channels (Email & Google Ads).
- Conduct A/B testing on checkout UX to improve conversion rates.

---

---

# 📌 Skills Demonstrated

- Data Cleaning  
- Exploratory Data Analysis  
- Funnel Analysis  
- KPI Development  
- Data Visualization  
- Business Intelligence Dashboarding  
- Python (Pandas)  
- Power BI  

---

# 👤 Author

**Aditya Chauhan**

Aspiring Data Analyst passionate about **data-driven decision making, business analytics, and visualization**.

LinkedIn: *(https://www.linkedin.com/in/aditya-chauhan-0b3826180/)*  
GitHub: *(https://github.com/Adityachauhan001386)*


