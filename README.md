# Customer_Shopping_Behavior_Analysis

## Overview
This project explores customer shopping behavior using transactional data to uncover insights into spending patterns, customer segments, and product preferences. It follows a complete data analytics workflow from data cleaning and exploratory analysis to SQL-based querying and interactive dashboard creation.

---

## Dataset
The dataset contains ~3,900 customer transactions with features such as:
- Customer demographics (Age, Gender, Location, Subscription Status)
- Purchase details (Item, Category, Amount, Season, etc.)
- Behavioral data (Discount usage, Purchase frequency, Ratings, Shipping type)

---

## Tools & Technologies
- **Python (Pandas, NumPy)** – Data cleaning & EDA  
- **SQL (PostgreSQL / MySQL / SQL Server)** – Data analysis  
- **Power BI** – Data visualization & dashboard  

---

## Project Workflow

### 1. Data Loading & Cleaning (Python)
- Loaded dataset using Pandas  
- Handled missing values and ensured data consistency  
- Performed feature engineering (e.g., age groups, purchase frequency)  

### 2. Exploratory Data Analysis (EDA)
- Analyzed customer behavior and spending patterns  
- Identified trends across categories, ratings, and demographics  

### 3. SQL Analysis
- Answered key business questions such as:
  - Revenue comparison by gender  
  - High-spending customers using discounts  
  - Top-rated and most purchased products  
  - Customer segmentation (New, Returning, Loyal)  
  - Subscription vs non-subscription behavior  

### 4. Dashboard (Power BI)
- Built an interactive dashboard to visualize:
  - Revenue trends  
  - Customer segments  
  - Product performance  
  - Purchase behavior insights  

---

## Dashboard
The Power BI dashboard file (`.pbix`) is included in this repository and can be opened using Power BI Desktop to explore the insights interactively.

---

## Key Insights
- Revenue trends vary across customer segments and demographics  
- Certain products consistently receive higher ratings and purchases  
- Discounts influence purchase behavior but vary by product  
- Loyal customers contribute significantly to overall revenue  

---

## How to Run

### Requirements
- Python 3.x  
- Power BI Desktop  
- PostgreSQL / MySQL / SQL Server  

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/customer_behaviour_analysis.git
cd customer_behaviour_analysis
