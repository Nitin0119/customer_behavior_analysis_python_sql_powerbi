# 🛒 Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes **3,900 customer purchase transactions** to uncover actionable insights into **spending behavior, customer segmentation, product performance, and revenue drivers**.  
The goal is to translate raw transactional data into **business-ready insights** that support strategic decision-making in marketing, loyalty, and pricing.

---

## 📊 Dataset Summary
- **Total Records:** 3,900 purchases  
- **Features:** 18 variables  
- **Average Purchase Value:** $59.76  
- **Average Customer Rating:** 3.75 / 5  

The dataset includes customer demographics, purchase details, subscription status, ratings, shipping type, and promotional behavior. :contentReference[oaicite:0]{index=0}

---

## 🧹 Data Preparation & Cleaning
All preprocessing was performed using **Python (pandas)** with a focus on analytical integrity.

**Key Steps:**
- Loaded and explored data using `df.info()` and `df.describe()`
- Imputed **37 missing review ratings** using median values grouped by product category
- Standardized column names to `snake_case`
- Engineered new features:
  - `age_group`
  - `purchase_frequency_days`
- Removed redundant column: `promo_code_used`
- Loaded the cleaned dataset into **PostgreSQL** for advanced SQL-based analysis and BI integration

---

## 💰 Revenue Insights by Gender
| Gender | Revenue | % of Total Revenue |
|------|--------|-------------------|
| Male | $157,890 | 67.74% |
| Female | $75,191 | 32.26% |

**Insight:** Revenue contribution is proportional to customer base size, indicating balanced spending behavior across genders.

---

## 👥 Customer Segmentation
| Segment | Customers | Percentage |
|------|----------|------------|
| Loyal | 3,116 | 80% |
| Returning | 701 | 18% |
| New | 83 | 2% |

**Insight:** Strong retention exists, but **701 returning customers** represent a clear opportunity for loyalty conversion.

---

## 🔁 Subscription Impact
- **Non-Subscribers:**  
  - 2,847 customers  
  - $170,436 revenue  
  - Avg spend: $59.87  

- **Subscribers:**  
  - 1,053 customers  
  - $62,645 revenue  
  - Avg spend: $59.49  

**Key Observation:**  
Average spend is similar, but **repeat buyers (>5 purchases)** are significantly higher among subscribers, validating subscription value in long-term retention.

---

## 🧤 Product Performance (Top Rated)
| Rank | Product | Avg Rating |
|----|--------|------------|
| 1 | Gloves | 3.86 |
| 2 | Sandals | 3.84 |
| 3 | Boots | 3.82 |
| 4 | Hat | 3.80 |
| 5 | Skirt | 3.78 |

**Insight:** High ratings cluster tightly, suggesting quality consistency across top categories.

---

## 🎯 Revenue by Age Group
- **Young Adults:** $62,143  
- **Middle-Aged:** $59,197  

Revenue is **evenly distributed**, indicating broad market appeal rather than dependence on a single demographic.

---

## 📈 Power BI Dashboard Insights
- **Category Performance:** Clothing dominates both revenue and sales volume
- **Shipping Behavior:**  
  - Express shipping users spend $60.48 on average  
  - Standard shipping users spend $58.46
- **Discount Analysis:**  
  - 839 customers used discounts yet still spent above average  
  - Indicates **price-insensitive high-value customers**

---

## 🧠 Strategic Recommendations
1. **Increase Subscription Adoption**  
   Convert the 73% non-subscriber base using exclusive benefits and retention offers.

2. **Strengthen Loyalty Programs**  
   Target the 701 returning customers with milestone-based rewards.

3. **Optimize Discount Strategy**  
   Reduce unnecessary discounting for high-spend customers to protect margins.

4. **Target High-Value Segments**  
   Focus marketing on:
   - Young adults
   - Express shipping users
   - Repeat purchasers

---

## 🛠️ Tools & Technologies
- **Python:** pandas, numpy  
- **SQL:** PostgreSQL  
- **BI & Visualization:** Power BI  
- **Data Skills:** EDA, Feature Engineering, Business Analysis

---

## 📎 Deliverables
- PowerPoint presentation (executive-ready)
- Cleaned dataset in PostgreSQL
- Power BI dashboard
- Business insights & recommendations

---

## 📌 Author
**Nitin Yadav**  
Data Analyst | Python | SQL | Power BI  

---

If this README does not get recruiter attention, the problem is not the content, it is where you are applying.
