# Ecommerce Festival Sales Analysis with Machine Learning

This project analyzes ecommerce sales data during a major Indian festival season to understand customer purchasing behavior, perform customer segmentation, and predict purchase amounts using Machine Learning techniques.

---

## 🎯 Project Objectives

- Perform complete data cleaning and exploratory data analysis (EDA)
- Analyze customer purchasing patterns across demographics and regions
- Segment customers using K-Means clustering
- Build a Machine Learning model to predict purchase amount using Random Forest
- Generate actionable business insights for sales and marketing teams

---

## 📂 Dataset Overview

The dataset contains anonymized ecommerce festival sales data with the following key features:

- Customer demographics: Gender, Age Group, Marital Status, State, Zone, Occupation  
- Product information: Product Category  
- Transaction details: Orders, Amount  

Dataset file used:
- `Diwali Sales Data.csv`

---

## 🧪 Project Workflow

### 1. Data Cleaning
- Removed null values
- Converted data types for numeric analysis
- Removed unnecessary columns

### 2. Exploratory Data Analysis (EDA)
- Sales analysis based on gender, age group, marital status, and occupation
- State-wise and zone-wise sales performance
- Product category performance using visualizations

### 3. Customer Segmentation (K-Means)
- Scaled numerical features using StandardScaler
- Applied K-Means clustering for customer segmentation
- Profiled each customer segment using spending and order patterns

### 4. Sales Prediction (Random Forest)
- Encoded categorical variables for ML readiness
- Trained a Random Forest Regressor to predict purchase amounts
- Evaluated the model using R² score and Mean Absolute Error
- Extracted feature importance to find key sales drivers

### 5. Business Insights
- Identified high-value customer segments
- Determined top-performing states and product categories
- Suggested targeting strategies for festival marketing campaigns

---

## 🛠 Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-Learn  
- Jupyter Notebook  

---

## 📁 Repository Contents

- `Diwali_Sales_Analysis_With_EDA_AND_ML_.ipynb` – Complete notebook with EDA and ML
- `Diwali Sales Data.csv` – Dataset used for analysis
- `requirements.txt` – Required Python libraries

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/AYUSHTIWARI7126/Ecommerce-Festival-Sales-ML.git
