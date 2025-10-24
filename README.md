# Sales analysis for market expansion in SuperStore, a global retail chain with Power BI
<img width="1333" height="815" alt="image" src="https://github.com/user-attachments/assets/1309e02a-3697-4164-817f-c1f04812c376" />


Author: Huỳnh Như Yến  
Date: 14/6/2025 <br>
Tool Used: Power BI

---
## 📑 Table of Contents  
1. [📌 Background & Overview](#-background--overview)  
2. [📂 Dataset Description & Data Modeling](#-dataset-description--data-structure)   
3. [📊 Key Insights & Visualizations](#-key-insights--visualizations)  
4. [🔎 Final Conclusion & Recommendations](#-final-conclusion--recommendations)

---
## 📌 Background & Overview
### 📖 What is this project about? 
This project analyzes sales performance and key products of Superstore, a global commercial company, in different operating markets. The objective is:
  - identify important markets
  - identify important products.


### 👤 Who is this project for?  
✔️ Senior managers <br>
✔️ Data analysts & business analysts <br>
✔️ Recruiters
 

###  ❓Business Questions:  
The project aims to solve questions: <br>
✔️ Identify markets with good sales performance <br>
✔️ Identify key products <br>
✔️ Provide actionable insights through Power BI dashboards 

### 🎯Project Outcome:  
Here are insights after the analysis: <br>
✔️ APAC, EU and US are the top three markets of the company. <br>
✔️ EMEA is a young and most potential market with the fastest year-over-year growth in sales. <br>
✔️ Technological products generate the most sales and profit to the company.

---
## 📂 Dataset Description & Data Modeling
#### Dataset Description
Dataset belongs to Superstore which is a global commercial company operating in 7 markets: Canada, US, EU, APAC, LATAM, EMEA, Africa.

Dataset includes 3 table: Orders, People and Returns:

- Orders table includes transaction data. There are 20 variables. Important variables used in this project are Order ID, Order Date, Ship Mode, Segment, Country, Market, Category, Sub-category, Sales, Quantity, Profit.

- People table includes data about sales managers in different regions. There are two variables: Person and Region.
  
- Returns table includes return data. There are two variables: Returned and Order ID. 

#### Data modeling
The custom date table is created by the author. _Measures table is created by the author to store all measures.

![image](https://github.com/user-attachments/assets/3a823955-d06f-4354-b656-66575b5bd64b)

Table relationships:
| From: table (column) | Relationship | To: table (column) |
|----------|----------|----------|
| Orders (Order Date) | One-to-many | dim_date (Date) |
| Orders (Order ID) | One-to-many | Returns (Order ID) |
| Orders (Region) | One-to-many| People (Region) |

---
## 3. Design thinking
### Step 1: Empathize 5W1H

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1677035c-6642-432e-82df-618715aec9a6" />

### Step 2: Define northstar metric(s) and point of view

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b15039c1-1d5f-4b25-875e-04d2be2b5fa2" />

### Step 3: Ideate

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b35a48d0-c7fd-4693-817b-aa8200885980" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4c3bfb56-2da2-4506-b2fb-dff0115cd215" />

### Step 4: Prototype 
<br>
See prototype in Section 4: Visualizations & Insights

---
## 📊 Visualizations & Insights
#### Layout 1: Sales performance analysis by market

![page 1_page-0001](https://github.com/user-attachments/assets/c30f0148-51e7-4ba2-b335-2d0f85f20790)

Key insights in 2014: <br>
✔️ The Asia-Pacific (APAC) market generates the highest sales at $1.2 millions while EU is the second biggest market with $1 millions in sales. The US is a lucratic market, generating the third largest sales at $0.7 millions. <br>
✔️ Even though sales in EMEA is relatively small at only 0.3M, this market experiences the fastest year-over-year growth. EU also has the second highest sales growth. <br>
✔️ Canada has the biggest profit margin at 26% while the sales is the smallest. <br>
✔️ Amongst 3 segments, consumer generates the highest sales in all markets while home office is the least important one. <br>
✔️ Amongst 3 product categories, technology contributes the largest sales in most markets. It is worth noting that APAC and LATAM have the highest proportion of sales generated from furnitures.

#### Layout 2: Sales performance analysis by product
![page 2_page-0001](https://github.com/user-attachments/assets/83af7c77-1415-45b8-ba84-0b22165db293)

Key insights in 2014: <br>
✔️ The sales of all three categories have significantly increased in period 2011-2014. <br>
✔️ In 2014, technology contributes the largest profit for the company. <br>
✔️ Standard class is the most popular ship mode. <br>
✔️ Phones, copiers and bookcases sub-categories generate the most sales for the company. <br>
✔️ Copiers, phones and bookcases are the most profitable sub-categories.

---
## 🔎 Final Conclusion & Recommendations
#### Key insights about good markets
- Asia-Pacific market is the most important market to the company.
- EMEA market is still a young market but has the highest year-over-year growth rate. <br>
👉👉👉 The company should invest more to expand its operation in this market.
- EU generates the second highest sales and has a strong YoY growth rate. <br>
👉👉👉 The company should focus on exploiting the potential of this market.

#### Key insights about key products
- Technological products, especially smartphones and copiers, are the most important to the company in terms of both sales and profit.
- Office supplies, especially bookcases, are the second important product category to the company.
- Tables sub-category is the only one which generates a loss of $30,000. <br>
👉👉👉 The company should consider to either improve the product quality or stop selling this sub-category.
