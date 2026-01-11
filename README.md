# 🚗 Car Sales Data Analysis (EDA)

## 📌 Overview
This repository contains an **Exploratory Data Analysis (EDA)** project focused on car sales data.  
The objective is to uncover meaningful insights related to customer demographics, vehicle preferences, and sales patterns using Python-based data analysis techniques.
---

## 🧾 Dataset Description
The dataset consists of structured car sales records including customer details, vehicle attributes, and dealer information.

### 📊 Key Features
- Customer Name  
- Gender  
- Annual Income  
- Engine Type  
- Transmission  
- Body Style  
- Dealer Region  

> Non-essential fields such as `Date` and `Dealer_Name` were removed during preprocessing to improve analysis clarity.

---

## 🛠️ Tech Stack
- **Python 3**
- **Pandas** – data manipulation and cleaning  
- **NumPy** – numerical computations  
- **Matplotlib** – foundational visualizations  
- **Seaborn** – advanced statistical visualizations  

---

## 🔍 Project Workflow

### 1️⃣ Data Ingestion
- Loaded CSV dataset into Pandas DataFrame  
- Performed initial inspection using `head()`, `info()`, and `describe()`

### 2️⃣ Data Cleaning
- Identified and handled missing values  
- Filled missing customer names using mode  
- Removed duplicate rows  
- Dropped irrelevant columns  

### 3️⃣ Exploratory Data Analysis
- Gender-based purchase analysis  
- Transmission preference comparison  
- Engine type distribution  
- Body style popularity  
- Regional sales distribution  

### 4️⃣ Statistical Insights
- Percentage-based comparisons  
- Grouped aggregations using `groupby()`  
- Distribution analysis for numerical features  

### 5️⃣ Data Visualization
- Histograms and bar plots  
- Distribution plots  
- Clean, readable charts using Seaborn  

---

## 📈 Sample Insights
- Majority buyer gender distribution  
- Automatic vs Manual transmission preference  
- Most popular car body styles  
- Regional contribution to total sales  

---
