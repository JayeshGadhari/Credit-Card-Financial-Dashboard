# 💳 Credit Card Financial Dashboard (Power BI)

## 📌 Project Overview  
The **Credit Card Financial Dashboard** provides an interactive analysis of **credit card transactions and customer behavior** using **Power BI**.  
It tracks key performance indicators such as **Revenue, Income, Interest Earned, Customer Satisfaction, and Transaction Volume** to help understand financial performance and customer trends.  

This project demonstrates skills in **SQL, Power Query, Data Modeling, DAX measures, and advanced visualization techniques** in Power BI.  

---

## 🚀 Features  
- 📊 **Customer Report Dashboard**  
  - Revenue, Income, Interest Earned, and Customer Satisfaction Score.  
  - Revenue breakdown by **Age Group, Gender, Education, Income Group, Marital Status, and State**.  
  - Customer segmentation by **Job Type and Dependent Count**.  

- 💳 **Transaction Report Dashboard**  
  - Revenue and Total Transaction Count by Quarter.  
  - Revenue by **Expenditure Type, Card Category, Use of Chip (Swipe/Chip/Online)**.  
  - Insights by **Customer Job, Education Level, and State**.  
  - Card Category performance (Blue, Silver, Gold, Platinum).  

- 🔍 **Interactive Filters**: Quarter, Gender, Week Start Date, Card Category.  
- ⚡ **Dynamic KPIs**: Automatically update with applied filters.  

---

## 🛠️ Tech Stack / Tools Used  
- **Visualization Tool**: Power BI Desktop  
- **Data Source**: Credit Card Customer & Transaction Dataset (CSV/SQL)  
- **Data Cleaning & Transformation**: Power Query  
- **Data Modeling**: Relationship modeling between fact and dimension tables  
- **DAX Measures**:  
  - `Total Revenue = SUM(Fact_Transactions[Revenue])`  
  - `Total Income = SUM(Fact_Transactions[Income])`  
  - `Total Interest = SUM(Fact_Transactions[Interest_Earned])`  
  - `Cust Satisfaction = AVERAGE(Fact_Customers[Cust_Satisfaction_Score])`  
  - `Total Transactions = COUNT(Fact_Transactions[Transaction_ID])`  

---


## 📂 Project Structure 
```
Credit-Card-Dashboard/
│
├── Customer.csv and Credit.csv                # Raw and cleaned datasets
├── images/                                    # Exported screenshots
├── Credit Card Financial Dashboard.pbix       # Power BI file
└── README.md                                  # Documentation

```


---

## 📸 Dashboard Preview  

### 📍 Customer Report  
![Customer Dashboard](images\Customer.jpg)  

### 📍 Transaction Report  
![Transaction Dashboard](images\Transaction.jpg)  

---

## 📊 Key Insights  
- 🔹 Total Revenue: **$55M** | Total Income: **$576M** | Interest Earned: **$8M**.  
- 🔹 Average Customer Satisfaction Score: **3.19**.  
- 🔹 Revenue highest among **40–50 age group** and **graduates**.  
- 🔹 **Blue Card** customers generated **$46M revenue** (dominant card category).  
- 🔹 Most transactions are through **Swipe (35M)**, followed by Chip (17M).  
- 🔹 Top Expenditure Categories: **Bills ($14M)**, **Entertainment ($10M)**, **Fuel & Grocery ($9M each)**.  

---



## 📂 Project Structure  
