# Sales analysis for market expansion in SuperStore, a global retail chain with Power BI
<img width="1333" height="815" alt="image" src="https://github.com/user-attachments/assets/1309e02a-3697-4164-817f-c1f04812c376" />


Author: Huỳnh Như Yến  
Tool Used: Power BI

---
## 📑 Table of Contents  
1. 📌 Background & Overview
2. 📂 Dataset Description & Data Modeling
3. 🧠 Design thinking
4. 📊 Visualizations & Insights  
5. 🔎 Recommendations

---
## 1. 📌 Background & Overview
### 📖 What is this project about? 
This project analyzes sales performance and key products of Superstore, a global commercial company, in different operating markets. The objective is:
  - identify important markets
  - identify important products.


### 👤 Who is this project for?  
✔️ Senior managers <br>
✔️ Data analysts & business analysts <br>
 

###  ❓Business Questions:  
The project aims to solve questions: <br>
✔️ Identify markets with good sales performance <br>
✔️ Identify key products <br>
✔️ Provide actionable insights through Power BI dashboards 

---
## 2. 📂 Dataset Description & Data Modeling
#### Dataset Description
Dataset belongs to Superstore which is a global commercial company operating in 7 markets: Canada, US, EU, APAC, LATAM, EMEA, Africa.

This project uses data from table Orders which include transaction data. There are 20 variables. Important variables used in this project are Order ID, Order Date, Ship Mode, Segment, Country, Market, Category, Sub-category, Sales, Quantity, Profit.

  
#### Data modeling
The custom date table is created by the author. _Measures table is created by the author to store all measures.

![image](https://github.com/user-attachments/assets/3a823955-d06f-4354-b656-66575b5bd64b)

---
## 3. 🧠 Design thinking
### Step 1: Empathize 5W1H

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1677035c-6642-432e-82df-618715aec9a6" />

### Step 2: Define northstar metric(s) and point of view

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b15039c1-1d5f-4b25-875e-04d2be2b5fa2" />

### Step 3: Ideate

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/faee0e07-61af-4c8b-bff1-3442fbcfabe4" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e40adb71-6f72-4223-a3a8-9195f1d0fa85" />


### Step 4: Prototype 
<br>
See prototype in Section 4: Visualizations & Insights

---
## 4. 📊 Visualizations & Insights
#### Layout 1: Overview

<img width="1067" height="616" alt="image" src="https://github.com/user-attachments/assets/19c3c8d4-e822-4c8e-ab86-72865a576c93" />

Observations:

#### 1. Revenue and profit increased steadily
- Total revenue doubles from $2.3M in 2011 to $4.3M in 2014. 
- Profit has increased steadily by around $0.1M each year. Profit margin has steadily remained between 11% and 12%, showing that revenue is driven by higher sales volume not by enhanced operational efficiency. 

#### 2. Technological products contribute most to total revenue
- Among three product categories, technology has contributed most to total revenue in all years. Revenue from technology has increased from $0.8M in 2011 to $1.6M in 2014.
- Revenue from office supplies is the second highest in all years. Revenue from office supplies has surged from $0.8M to $1.4M during 2011-2014.
- Revenue from furniture has also risen steadily by around $0.1M each year, reaching $1.3M in 2014.

#### 3. Consumer segment drives the highest sales
- Consumer segment has earned most revenue, accounting for around 50% of total sales. Hence, consumer segment is the most important to the company.

#### 4. APAC is the largest market in terms of revenue and profit
- APAC ranks the first position in terms of revenue and profit. The number of customers in APAC region is approximate to the next two biggest regions, EU and US but the total revenue significantly exceeds revenues from these two regions. That indicates that the spending of a customer in APAC is significantly higher than other regions.

#### 5. Canada has the highest profit margin
- Total revenue from Canada is the smallest but its profit margin is the highest, at 26.62%. That indicates that Canada is a new market but worth investing and expanding. 

#### 6. EMEA has the lowest profit margin
- The profit margin of EMEA is the lowest at 5.45% and worth further investigation on the reason. 

#### Layout 2: Market analysis

<img width="1143" height="663" alt="image" src="https://github.com/user-attachments/assets/af1e5a54-2b76-4f6f-a142-76ae7665da68" />

Observations:
#### 1. Revenue and profit distribution
- APAC, EU and US generate most revenue at $3.6M, $2.9M and $2.3M respectively. Their profits are also highest at $0.43M, $0.37M and $0.28M respectively.
- Total revenue from Canada is just %0.1M but its profit margin is highest at 26.62%.

#### 2. Consumer segment contributes over 50% of revenues in all makrets
- The revenue from consumer accounts for over 50% of total revenue in all market, indicating that this segment is the most important.

#### 3. Office supplies are important in Canada
- While technology dominates in other regions, office supplies generate the highest revenue in Canada.
  
#### Layout 3: Product analysis

<img width="1148" height="658" alt="image" src="https://github.com/user-attachments/assets/0c1ac516-3b35-4210-aeb6-a85e9f753ca4" />

Observations:

#### 1. Top products
- Phones contribute most to total revenue with the total of $1.71M.
- Revenues from copiers and chairs are the second and third highest, at $1.51M and $1.50M respectively.

#### 2. Profitable profits with high growth rate
- Copiers have the highest profit, around $0.25M, and year-over-year revenue growth rate, around 58%.
- Even though the yoy growth rate of phones is not high compared to other products, they are the second profitable, generating over $0.2M in profit.
- Appliances and bookcases alo generate good profit and have high yoy growth rate.
  
#### 3. Tables generate loss
- Even though the sales of tables is good, at $0.76M, their profit is negative. Considering that tables occupy large storage space and high delivery cost but generate losses, the company should consider to stop selling them. 
---
## 5. 🔎 Recommendations
| Strategy | Insight | Recommendation |
|-----------|-----------|-----------|
| Market expansion | - Canada has the highest profit margin at over 26% despite smallest revenue. <br> - EMEA and Africa have the highest yoy revenue growth rates, at 59.8% and 56.5% respectively. <br> - EU is already a large market with second highest revenue while the growth potential is still high.| - Expand to Canada but carefully focus on office supplies which generate high profit margins. <br> - Continue to expand to EMEA and Africa; however, EMEA has very low profit, the choice of products to sell in this region should be reconsidered. |
| Product optimization | - Technological products, especially phones and copiers, generate highest revenues and are profitable. <br> - Office supplies such as chairs, bookcases and appliances generate good revenue and have high yoy growth. <br> - Tables earn good revenue but incur loss. | - Continue to boost the sales of copiers which has highest growth potential. <br> - Consider to stop selling tables since they generate loss. Or consider to lower the storage cost or delivery cost of tables.  |



