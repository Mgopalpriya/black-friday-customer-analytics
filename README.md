# Black Friday Customer Analytics

## 📊 Project Overview
This project analyzes customer purchasing behavior during Black Friday sales to identify high-value customer segments, understand demographic and city-level performance, and deliver actionable business insights using Python and Power BI.

The analysis focuses on customer segmentation, Customer Lifetime Value (CLV), loyalty behavior, and category performance to support targeted marketing and retention strategies.

---

## 🎯 Business Objectives
- Identify profitable customer segments based on spending and purchase behavior
- Understand the impact of demographics (age, gender, city) on sales
- Analyze product category contribution to total revenue
- Provide data-driven recommendations for post-sale engagement and loyalty programs

---

## 🧾 Dataset
- **Source:** Black Friday Sales Dataset (Kaggle)
- **Records:** ~550,000 transactions
- **Key Fields:**  
  User_ID, Product_ID, Gender, Age, Occupation, City_Category,  
  Stay_In_Current_City_Years, Marital_Status, Product_Category_1/2/3, Purchase

> Note: Dataset represents a single Black Friday sales period with no time-series data.

---

## 🛠 Tools & Technologies
- **Python:** pandas, numpy, scikit-learn, scipy, statsmodels
- **Visualization:** Power BI
- **Data Processing:** CSV-based pipeline
- **Version Control:** GitHub

---

## 🔍 Key Analysis Performed
- Data cleaning and validation
- Feature engineering (CLV, Frequency, Category Breadth, City Loyalty Index)
- Exploratory Data Analysis (EDA)
- Customer segmentation using K-Means clustering
- Statistical validation using T-Test and ANOVA
- Interactive Power BI dashboard development

---

## 👥 Customer Segments Identified
| Segment | Description |
|------|-----------|
| **Budget Buyers** | Low CLV, high volume, price-sensitive customers |
| **Loyal Shoppers** | Moderate CLV with consistent repeat behavior |
| **Premium Champions** | High CLV, high frequency, mostly Metro customers |

---

## 📈 Key Business Insights
- Tier-2 cities contribute ~40% of total revenue
- Premium Champions show the highest CLV and loyalty
- Age group 26–35 drives the majority of transactions and spend
- Occupations 1, 4, and 7 account for over 60% of total sales
- Metro customers purchase less frequently but spend significantly more per transaction

---

## 💡 Strategic Recommendations
- Launch city-specific loyalty programs for Tier-2 customers
- Upsell premium bundles to high-CLV Metro customers
- Focus marketing spend on the 26–35 age group
- Design reactivation campaigns for low-value, high-volume customers

---

## 📊 Dashboard
The Power BI dashboard provides:
- Executive overview of revenue and customer KPIs
- Customer segmentation analysis
- Product and category performance
- City and demographic insights
- Comparative cluster performance

📁 Dashboard file available in the `dashboard/` folder.

---

## 📂 Repository Structure

black-friday-customer-analytics/
│
├── README.md
├── notebooks/ # Python analysis notebooks
├── data/ # Cleaned and feature-engineered datasets
├── dashboard/ # Power BI (.pbix) file
├── docs/ # Detailed project documentation
├── presentation/ # Executive insights deck (PDF)
└── visuals/ # Dashboard screenshots



---

## ⚠️ Limitations & Future Scope
- Data limited to one sales period
- No timestamp available for recency analysis
- Product category names are masked

**Future Enhancements:**
- Time-series analysis with multi-period data
- Predictive modeling (churn, sales forecasting)
- Recommendation system for personalized offers

---

## 👤 Author
**Manoranjan Gopal Priya**  
Data Analyst | CX & Operations Analytics  

