# ☕ Coffee Shop Business Analysis

### 📊 Data-Driven Insights for a Growing Coffee Business

This project analyzes transactional data from a coffee shop to identify sales trends, customer behavior patterns, and opportunities for business growth.  
The analysis focuses on **peak hours**, **top-selling products**, and **revenue patterns**, aiming to provide **strategic recommendations** for increasing sales and optimizing operations.

---

## 🧭 1. Project Overview

The main goal of this analysis is to understand when and how the coffee shop performs best — and where improvements can be made.  
Key questions addressed:
- What are the **busiest hours and days** of the week?
- Which **products** generate the highest **sales volume and revenue**?
- How do sales evolve **month by month**?
- What **actions** can be taken to increase revenue during slower periods?

---

## 📂 2. Dataset Overview

- **File:** `Coffee Shop Sales.xlsx`  
- **Description:** Transaction-level data including product category, quantity, price, date, and time.  
- **Added Columns:**  
  - `Revenue` = Price × Quantity  
  - `Month` (derived from transaction date)  
  - `Hour` (derived from timestamp)  
- **Data Period:** *(Specify the months covered, e.g., Jan–Jun 2023)*  
- **Tools Used:** Microsoft Excel / Power BI  
- **Data Type:** Simulated business data for analysis and visualization purposes.  

---

## ⚙️ 3. Methodology

1. **Data Cleaning**  
   - Removed duplicates and null values  
   - Standardized date and time formats  

2. **Feature Engineering**  
   - Created new columns for `Revenue`, `Month`, and `Hour`  

3. **Exploratory Analysis**  
   - Built Pivot Tables to analyze sales trends by month, day, hour, and product category  

4. **Dashboard Creation**  
   - Designed an interactive dashboard (Excel / Power BI) with slicers for dynamic filtering by location or category  

---

## 📈 4. Key Insights

### 🗓️ Monthly Sales Trends
- Revenue increased from **$81,678 in January** to **$166,486 in June**, showing steady growth.  
- A slight dip in **February** — possibly due to seasonality or lower customer traffic.  
- Sharp recovery and growth in **April–May**, suggesting successful promotions or seasonal factors.

### 🕒 Peak Hours & Customer Behavior
- The **morning rush (8 AM – 10 AM)** drives the majority of transactions.  
- Noticeable decline in the afternoon — indicating potential for “after-lunch” campaigns.  
- **Friday and Thursday** are the busiest days (~21K transactions), while **Saturday** is the slowest (~20.5K).

### ☕ Product Performance
- **Top Categories:**  
  - Coffee – ~58,416 transactions  
  - Tea – ~45,449 transactions  
- **Top Product:** *Brewed Chai Tea* (~17,183 transactions, $77,082 in revenue)  
- **Cross-sell Potential:** pastries, scones, biscotti — often purchased with beverages.  

---

## 💡 5. Recommendations

### 1. Optimize Morning Performance  
- Capitalize on the 8–11 AM rush with **breakfast bundles** and **loyalty discounts**.  
- Introduce **premium espresso or seasonal drinks** during peak hours.

### 2. Boost Afternoon Sales  
- Implement **“Happy Hour” promotions** after 12 PM.  
- Offer **limited-edition drinks** available only in the afternoon.

### 3. Expand Product Strategy  
- Increase **tea and specialty drink** options — high demand and consistent growth.  
- Encourage **cross-selling** pastries or snacks with beverages.

### 4. Improve Weekend Engagement  
- Launch **“Weekend Specials”** to drive Saturday foot traffic.  
- Use **social media campaigns** on Fridays to boost weekend awareness.

---

## ⚠️ 6. Limitations & Future Work

- Dataset covers only *six months* — a longer time frame would improve trend reliability.  
- Only **sales revenue** analyzed — no cost or profitability data included.  
- Lacks **customer segmentation** (new vs. returning customers).  
- Future work could include:  
  - Customer lifetime value (CLV) analysis  
  - Product profitability breakdown  
  - Loyalty and retention metrics

---

## 📚 7. Key Takeaways

- The coffee shop shows **consistent month-to-month growth**.  
- **Morning sales dominate** revenue — strong customer habit.  
- **Afternoon hours** and **weekends** represent clear improvement opportunities.  
- Focused campaigns and menu diversification could increase total revenue by **10–20%** in the short term.
