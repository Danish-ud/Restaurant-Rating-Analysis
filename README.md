
# Restaurant Rating Analysis 

Welcome to the Restaurant Rating Analysis project! This repository contains a comprehensive data analysis and visualization of restaurant ratings in Mexico. The primary goal of this project is to derive insights  from multiple datasets related to restaurants and present them through a clean dashboard.

---

## 📊 Project Overview

In this project, I performed a detailed analysis of restaurant ratings using Python (Pandas) for data cleaning and transformation, and Power BI for data visualization. The datasets include various aspects of restaurants such as customer ratings, cuisines, cost, location, and service quality.

---

## 🧠 Objectives

- Understand rating patterns among restaurants in Mexico.
- Identify factors influencing customer ratings (e.g., location, price range, cuisines).
- Discover trends and anomalies using data visualization techniques.

---

## 🛠️ Tools & Technologies

- **Python** – Used for data cleaning, transformation, and merging of datasets.
- **Pandas** – For data manipulation and preprocessing.
- **Power BI** – To create dynamic and dashboards and visualizations.

---

## 📁 Dataset Description

The project consists of **5 relational tables**, which were merged to create a single, analysis-ready dataset. These include:

1. **Consumers Table** – It has details of consumers like name, ID, location, occupation, marital status, drink or smoking preferences .
2. **comsumer preferences Table** – consumer id, preferred cuisine .
3. **restaurants Table** – It has basic details about the restaurants, location .
4. **restaurant cuisines Table** – Information about restaurants, cuisine they offer.
5. **ratings** – customer id, restaurant id, rating.

- [`Data_Cleaning_Analysis.ipynb`](notebooks/Data_Cleaning_Analysis.ipynb)
---

## 🧹 Data Cleaning & Transformation

- Removed duplicate, and inconsistent data.
- Handled missing, and Null values with at most precision.
- Standardized the whole data set.
- Converted numerical columns to proper data types.
- Merged all datasets into a single table using primary keys  like `restaurant_id` and  `Consumer_d`.

All cleaning operations were performed using Python’s **Pandas** library for efficiency and reproducibility.

---

## 📈 Visualizations (Power BI Dashboard)

Power BI was used to create an interactive dashboard, highlighting:

- Average ratings by city and cuisine
- Top 10 and bottom 10 restaurants based on customer reviews
- Cost vs rating distribution
- Heatmaps of restaurant density and rating distribution
- Filters for dynamic exploration by cuisine, city, and cost range

> 📌 A link to the published Power BI dashboard.

---

## 🧩 Key Insights

- Mexican restaurants in certain cities consistently scored higher.
- Fusion and authentic Mexican cuisine tend to receive better ratings.
- Restaurants with moderate pricing often outperform both low and high-cost counterparts in ratings.
- Some locations have a high density of poorly rated establishments.

---
## 🔗 Files in This Repository

- [`Data_Cleaning_Analysis.ipynb`](notebooks/Data_Cleaning_Analysis.ipynb) – Python code for cleaning and merging the datasets.
- [`Restaurant_Analysis.pbix`](Restaurant_Analysis.pbix) – Power BI dashboard file (open with Power BI Desktop).
- [`/screenshots`](screenshots/) – Contains visualizations from the Power BI dashboard.

## 📂 Repository Structure

