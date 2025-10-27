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
#### Layout 1: Overview

<img width="1067" height="616" alt="image" src="https://github.com/user-attachments/assets/19c3c8d4-e822-4c8e-ab86-72865a576c93" />

Observations:

#### 1. Revenue and profit increased steadily
Total revenue doubles from $2.3M in 2011 to $4.3M in 2014. 
Profit has increased steadily by around $0.1M each year. Profit margin has steadily remained between 11% and 12%, showing that revenue is driven by higher sales volume not by enhanced operational efficiency. 

#### 2. Technological products contribute most to total revenue
Among three product categories, technology has contributed most to total revenue in all years. Revenue from technology has increased from $0.8M in 2011 to $1.6M in 2014. Revenue from office supplies is the second highest in all years. Revenue from office supplies has surged from $0.8M to $1.4M during 2011-2014. Revenue from furniture has also risen steadily by around $0.1M each year, reaching $1.3M in 2014.

#### 3. Consumer segment drives the highest sales
Consumer segment has earned most revenue, accounting for around 50% of total sales. Hence, consumer segment is the most important to the company.


#### Layout 2: Market analysis

<img width="1143" height="663" alt="image" src="https://github.com/user-attachments/assets/af1e5a54-2b76-4f6f-a142-76ae7665da68" />

Observations:

#### Layout 3: Product analysis

<img width="1148" height="658" alt="image" src="https://github.com/user-attachments/assets/0c1ac516-3b35-4210-aeb6-a85e9f753ca4" />

Observations:

---
## 🔎 Recommendations


#### Key insights about key products
- Technological products, especially smartphones and copiers, are the most important to the company in terms of both sales and profit.
- Office supplies, especially bookcases, are the second important product category to the company.
- Tables sub-category is the only one which generates a loss of $30,000. <br>
👉👉👉 The company should consider to either improve the product quality or stop selling this sub-category.
