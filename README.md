# CreditCard-Transaction-Analysis-PowerBI

## 📘 Project Overview
This project analyzes over **1.8M credit card transaction records** to extract insights about customer spending behavior and fraud detection.  
The dataset was provided as a **flat file**, which I cleaned and modeled into a **Star Schema** using Power Query.

-<a href="https://app.powerbi.com/viewr=eyJrIjoiYzlhZjM4NGMtNGI2ZS00YTJkLTk1YWYtZDI5OGE2MGEyYzAzIiwidCI6IjJiYjZlNWJjLWMxMDktNDdmYi05NDMzLWMxYzZmNGZhMzNmZiIsImMiOjl9">🔗 **Live Dashboard:** [View on Power BI Service] 


## 🧩 Data Preparation
- Cleaned raw dataset using **Power Query**.
- Built a **Star Schema** separating:
  - **Fact Table**: Transactions (CardID, MerchantID, Amount, Date, FraudFlag, etc.)
  - **Dimension Tables**: Cardholder-info, Merchant-info,calenderDate.
- Loaded model into Power BI for analysis.
  <a href='

## 📊 Dashboard 1: Customer Demographics & Spending Insights  
**Who Spends, How, and Where?**
<img width="1514" height="675" alt="DashPage1" src="https://github.com/user-attachments/assets/ecb2997c-6a3e-4ea6-8b8b-0a3cdf634705" />


## 🧠 Dashboard 2: Fraud & Merchant Insights
<img width="1495" height="716" alt="Dashpage2" src="https://github.com/user-attachments/assets/bc5e3f74-1140-439a-be7b-343db9950133" />


## 🔍 Key Insights
- Spending is highest among customers aged **30–40**.  
- Certain job groups contribute most to overall spending.  
- Fraud patterns vary significantly across categories and merchants.  
- Star Schema design improved data performance and scalability.

## 🛠️ Tools & Technologies
- **Power BI**
- **Power Query**
- **DAX**
- **Data Modeling (Star Schema)**
