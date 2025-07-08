# 📊 Telco Customer Churn Analysis

## 📝 **Objective**
The objective of this project is to analyze customer churn data to identify key factors and reasons behind churn. These insights help businesses take **data-driven actions** to reduce customer loss, improve retention, and enhance overall business performance.

---

## 🔧 **Problem Statement**
Customer churn is a major challenge for telecom companies as acquiring new customers is more costly than retaining existing ones. The problem is to **identify customers likely to churn** and understand the key factors driving their decision, enabling proactive retention strategies.

---

## 📁 **Dataset Description**
- **Source:** Kaggle – Telecom Customer Churn Dataset
- **Total Records:** 7,043 rows
- **Total Features:** 20 columns

### 🔑 **Key Features**
- **Demographics:** Gender, SeniorCitizen, Partner, Dependents  
- **Account Info:** Tenure, Contract, PaperlessBilling, PaymentMethod  
- **Service Subscriptions:** PhoneService, MultipleLines, InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies  
- **Billing:** MonthlyCharges, TotalCharges  
- **Target:** Churn (Yes/No)

---

## 🛠️ **Tools Used**
- **Excel:** Initial data exploration  
- **Python:** Data cleaning, preprocessing, feature engineering, and EDA using Pandas, Matplotlib, Seaborn  
- **Power BI:** Interactive dashboard and business insights visualization

---

## ⚙️ **Steps Followed**

### ✅ **1. Data Cleaning**
- Removed blanks and treated missing values  
- Created ‘Tenure Period’ column to categorize tenure

### ✅ **2. Exploratory Data Analysis (EDA)**
- Univariate and bivariate analysis to identify churn patterns  
- Analyzed churn rates by demographics, services, and payment methods

### ✅ **3. Feature Engineering**
- Created new features to improve analysis clarity (e.g., Tenure Period)

### ✅ **4. Power BI Dashboard Creation**
- **KPI Cards:** Total customers, churned customers, churn rate, average charges, average tenure  
- **Bar Charts:** Churn by gender, contract type, payment method, tech support, online services  
- **Donut Chart:** Overall churn distribution  
- **Slicers:** Gender, contract type, payment method, internet service, tenure period for dynamic analysis

---

## 💡 **Key Findings**
1. **Churn Rate:** ~26.5% overall  
2. **Contract Impact:** Month-to-month contracts have 43% churn vs. two-year contracts at 3%  
3. **Tenure Impact:** Customers with <1 year tenure churn the most (~40%)  
4. **Payment Method:** Electronic check users churn the highest (45%)  
5. **Tech Support:** Customers without tech support churn at ~37%, vs. ~15% with support  
6. **Online Services:** Customers without online security or backup churn at ~42%

---

## 📈 **Business Recommendations**
- Promote long-term contracts with discounts  
- Implement targeted renewal offers for customers nearing 10-12 months tenure  
- Optimize mid-tier pricing (₹60–₹95) to reduce churn  
- Bundle tech support, online security, and backup services  
- Encourage electronic check users to shift to auto-payments via rewards  
- Develop loyalty programs targeting single customers to improve retention

---

## 🔚 **Conclusion**
This analysis guides **data-driven strategies to reduce churn by 10-15%**, improving customer lifetime value and overall business profitability.

---

## 🚀 **How to Run**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/telco-customer-churn-analysis.git
