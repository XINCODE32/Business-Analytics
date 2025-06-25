# 📊 Yandex.Afisha Marketing Optimization Project

Welcome to the Yandex.Afisha Analytics Internship Project!  
In this project, we analyze product usage, user behavior, revenue patterns, and marketing ROI to **optimize advertising expenses** for Yandex.Afisha.

---

## 🎯 Objective

The goal of this analysis is to help the Yandex.Afisha team answer three core business questions:

1. **How people use the product** (sessions, retention, device behavior)
2. **When and how users convert** (orders, cohort behavior)
3. **How much each customer brings and costs** (LTV, CAC, ROI)

We provide actionable recommendations for smarter marketing investments based on data from:
- Server visit logs
- Orders dataset
- Marketing spend reports

---

## 📁 Dataset Files

Place these CSV files in the `./datasets/` directory:

| File | Description |
|------|-------------|
| `visits_log_us.csv` | User sessions data (visit logs) |
| `orders_log_us.csv` | Transaction history (orders) |
| `costs_us.csv` | Daily marketing spend by source |

---

## 🧠 Project Workflow

### Step 1: Data Preparation

- Import and load the datasets
- Convert timestamps to datetime format
- Ensure correct data types for revenue, cost, and user ID columns
- Handle missing values and duplicates
- Optimize memory usage (e.g., categoricals)

---

### Step 2: Product Analytics

- 👥 **User activity**: DAU, WAU, MAU over time
- 🕓 **Session metrics**:
  - Number of sessions per user per day
  - Average session duration
- 📈 **User retention**: Weekly retention by cohorts

---

### Step 3: Sales Analytics

- 📦 **Conversion lag**: Days between first session and first purchase
- 🔁 **Repeat orders**: Number of orders per user
- 💵 **Average check**: Revenue per order
- 📊 **Lifetime Value (LTV)**: Cumulative revenue per user cohort

---

### Step 4: Marketing Analytics

- 💰 **Total spend**: Overall and by channel over time
- 📥 **Customer Acquisition Cost (CAC)** = Total cost / New customers
- 📈 **Return on Investment (ROI)** = (LTV - CAC) / CAC
- 📱 **Device and Source analysis**:
  - Compare performance across mobile/desktop and source IDs

---

### Step 5: Recommendations

- Top-performing **marketing channels** by ROI and CAC
- Best **cohorts** in terms of LTV and retention
- Strategic **budget allocation** advice for next campaigns

---

## 📊 Example Metrics

| Metric | Sample Output |
|--------|---------------|
| MAU | 84,532 |
| Avg. Session Duration | 4m 12s |
| Conversion Lag (avg) | 2.1 days |
| Avg. LTV per cohort | $14.32 |
| Best ROI Source | Google Ads (ROI = 120%) |

---

## 📚 Tech Stack

- **Python**: pandas, numpy, datetime, matplotlib, seaborn
- **Jupyter Notebook**: EDA and visual storytelling
- **Data Analysis Concepts**: Cohort analysis, retention curves, unit economics

