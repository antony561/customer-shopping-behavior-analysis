# Customer Shopping Behavior Analysis

![Dashboard Preview](dashboard_preview.png)

## 📌 Overview
This end-to-end data analytics project analyzes customer shopping 
behavior to identify key revenue drivers, customer segments, and 
product demand patterns. The goal is to provide actionable insights 
that support business decisions related to marketing, customer 
targeting, and product strategy.

---

## 🎯 Business Problem
A leading retail company wants to better understand its customers' 
shopping behavior to improve sales, customer satisfaction, and 
long-term loyalty. The management team has noticed changes in 
purchasing patterns across demographics, product categories, and 
sales channels.

**Key Question:** How can the company leverage consumer shopping 
data to identify trends, improve customer engagement, and optimize 
marketing and product strategies?

---

## 🛠️ Tools & Technologies
- **Python (Pandas)** — Data cleaning and preprocessing
- **SQL (PostgreSQL)** — Business analysis and querying
- **Power BI** — Interactive dashboard and visualisation

---

## 🔄 Project Workflow

### 1. Data Cleaning (Python)
- Dataset: 3,900 customers, 18 features
- Handled 37 missing values in Review Rating using category-wise median imputation
- Standardised column names — lowercase with underscores
- Created `age_group` column using pd.qcut (Young Adult, Adult, Middle-aged, Senior)
- Created `purchase_frequency_days` — mapped text frequency to numeric values
- Removed duplicate column `promo_code_used` (identical to `discount_applied`)

### 2. Business Analysis (SQL — PostgreSQL)
Wrote 10 business queries covering:
- Revenue by gender and age group
- Customer segmentation (New, Returning, Loyal)
- Subscription impact on revenue
- Top products and categories
- Discount usage analysis
- Repeat buyer behaviour

### 3. Data Visualisation (Power BI)
Built an interactive dashboard featuring:
- KPI Cards — Total Revenue, Total Customers, Avg Purchase, Avg Rating
- Revenue by Category bar chart
- Customer Segments bar chart
- Top Products bar chart
- Subscription Status donut chart
- Slicers — Gender, Category, Subscription Status, Shipping Type

---

## 📊 Dashboard Preview
![Dashboard](dashboard_preview.png)

---

## 🔍 Key Insights
- Male customers generate **68% of total revenue** ($157,890 vs $75,191)
- **73% of customers are non-subscribers** — major conversion opportunity
- Loyal customers (10+ purchases) make up **~77%** of the customer base
- Clothing is the **top revenue category** at ~$103K
- **Jewelry, Pants and Undergarments** are the top 3 selling products
- Most repeat buyers are non-subscribers — opportunity to drive subscriptions
- All age groups contribute similarly to revenue — no dominant demographic

---

## 💡 Recommendations
- Target male customers with premium and upsell campaigns
- Launch subscription conversion campaign for loyal non-subscribers
- Promote top rated products in marketing materials
- Reward loyal customers with exclusive discounts
- Review discount strategy to ensure it drives volume not just reduces margins
- Plan inventory around top selling products across all categories

---

## 📁 Project Files
| File | Description |
|---|---|
| `data_cleaning_eda.ipynb` | Python data cleaning and EDA |
| `business_analysis_queries.sql` | 10 SQL business analysis queries |
| `customer_shopping_dashboard.pbix` | Power BI interactive dashboard |
| `customer_shopping_behavior.csv` | Raw dataset |
| `dashboard_preview.png` | Dashboard screenshot |
| `Customer_Shopping_Analysis_Report.pdf` | Full project report |

---

## 📬 Contact
- **GitHub:** github.com/antony561
- **LinkedIn:** [Your LinkedIn URL]
