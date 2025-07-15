# 📊 Swiggy Delivery Executive Performance Dashboard

This project is a complete Business Analyst case study focused on evaluating and visualizing the performance of delivery executives across multiple cities for a month. It simulates real-world operational analysis using Python and Excel.

---

## ✅ What I Did — Step-by-Step Breakdown

### 🧪 1. Data Generation (100K Rows using Python)
I generated a large-scale dataset of **100,000 food delivery records** using Python. The dataset captures realistic behavior across **8 cities** including:
- Delivery IDs
- Order timestamps
- Ratings
- Delivery performance

Python was used to automate the creation and structuring of data efficiently, making it easy to scale and analyze.

---

### 🗂️ 2. Raw Data Preparation
The generated dataset was exported to Excel as **"Raw Data"**. I enriched it with the following helper columns:
- `week_num` → calendar week based on order date (Monday–Sunday)
- `delivery_time_mins` → time taken from pickup to delivery
- `on_time_flag` → binary flag to indicate if delivery was within 40 minutes

---

### 📊 3. Performance Aggregation via Pivot Table
I created Excel Pivot Tables to summarize performance metrics **per delivery person, per city, per week**. The key metrics calculated were:
- Average Rating
- On-Time Delivery Percentage
- Total Orders Delivered
- Total Order Value

---

### 🏆 4. Ranking System for Top 5 Executives
To fairly evaluate performance, I implemented a **scoring model** that weighted each metric:
- Ratings
- Punctuality (On-time delivery)
- Order count
- Revenue generated

This system helped surface the **Top 5 delivery executives** in each city every week.

---

### 📈 5. Interactive Dashboard Design
Built an Excel-based **interactive dashboard** that allows business managers to:
- **Filter** by `City` and `Week Number`
- View the **Top 5 Delivery Executives**
- Analyze KPIs like:
  - Final score
  - Total orders delivered
  - Average delivery rating
  - Total revenue
  - Delivery punctuality

The dashboard provides a **clear and visual way to recognize high performers** and draw actionable insights.

---

## 📁 Files Included
- `swiggy_orders_raw.xlsx` — generated dataset with helper columns
- `pivot_analysis.xlsx` — pivot table for KPI aggregation
- `dashboard.xlsx` — slicer-based interactive dashboard for performance evaluation
- `dashboard_final_score.xlsx` — includes scoring logic and ranked results

---

## 💡 Tools & Tech
- Python (Pandas, NumPy, Faker)
- Microsoft Excel (Pivot Tables, Slicers, Conditional Formatting)

---

## 📬 Contact
Feel free to connect if you have questions or feedback!

