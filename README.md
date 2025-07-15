
# Restaurant Rating Analysis 

Welcome to the Restaurant Rating Analysis project! This repository contains a comprehensive data analysis and visualization of restaurant ratings in Mexico. The primary goal of this project is to derive insights  from multiple datasets related to restaurants and present them through a clean dashboard.

---
##  Table of Contents

- [Project Overview](#Project-Overview)
- [Objectives](#Objectives)
- [Tools and Technologies](#Tools--Technologies)
- [Dataset Description](#Dataset-Description)
- [Data Cleaning and Transformation](#data-cleaning-&-transformation)
- [Visualizations (Power BI Dashboard)](#visualizations (power bi dashboard))
- [Understanding Power bi Dashboards](#Understanding-Power-bi-Dashboards)
- [Key Insights](#key-insights)
- [Key Insights](#🧩-key-insights)
- [Key Insights](#🧩Key-Insights)
- [Key Insights](#-🧩key-insights)



##  Project Overview

In this project, I performed a detailed analysis of restaurant ratings using Python (Pandas) for data cleaning and transformation, and Power BI for data visualization. The datasets include various aspects of restaurants such as customer ratings, cuisines, cost, location, and service quality.

---

##  Objectives

- Understand rating patterns among restaurants in Mexico.
- Identify factors influencing customer ratings (e.g., location, price range, cuisines).
- Discover trends and anomalies using data visualization techniques.

---

##  Tools & Technologies

- **Python** – Used for data cleaning, transformation, and merging of datasets.
- **Pandas** – For data manipulation and preprocessing.
- **Power BI** – To create dynamic and dashboards and visualizations.

---

##  Dataset Description

The project consists of **5 relational tables**, which were merged to create a single, analysis-ready dataset. These include:

1. **Consumers Table** – It has details of consumers like name, ID, location, occupation, marital status, drink or smoking preferences .
2. **comsumer preferences Table** – consumer id, preferred cuisine .
3. **restaurants Table** – It has basic details about the restaurants, location .
4. **restaurant cuisines Table** – Information about restaurants, cuisine they offer.
5. **ratings** – customer id, restaurant id, rating.

- 🔗[`Restaurant Raw Dataset`](Raw_Dataset.zip)
---

##  Data Cleaning & Transformation

- Removed duplicate, and inconsistent data.
- Handled missing, and Null values with at most precision.
- Standardized the whole data set.
- Converted numerical columns to proper data types.
- Merged all datasets into a single table using primary keys  like `restaurant_id` and  `Consumer_d`.
- Finded trends in the data set by Exploratory Data Analysis

All cleaning operations were performed using Python’s **Pandas** library for efficiency and reproducibility.

-🔗 [`Cleaned Data set`](Rating_analysis.zip)

-🔗 [`Jupyter Note book`](Rating.ipynb)


---

##  Visualizations (Power BI Dashboard)

Power BI was used to create an interactive dashboard, highlighting:

- Which are the  most running restaurants.
- What is the impact of Customers Demographoc on the Rating.
- Which Cuisines are Rated higher.
- Does Restaurant Facilities has an impact on the Rating.

- 🔗 [`Power Bi Dashboard `](Restaurant rating.pbix)


--------
## Understanding Power bi Dashboards.

![`Customer Pattern Screen shot`](https://github.com/Danish-ud/Restaurant-Rating-Analysis/blob/main/Customer%20Data%20analyze.png)


  ### Customer data who Rated Restaurants Demographics.

  - This dashboard provides key insights into consumer preferences and demographics, enabling data-driven decisions for targeted marketing and service optimization.

  - Cuisine Preference: Mexican cuisine stands out as the most favored option by a significant margin, indicating a strong consumer preference for flavorful, spicy dishes. Restaurants offering high-quality Mexican food are likely to attract more customers.

  - Geographic Distribution: A notable concentration of ratings comes from San Luis Potosí, suggesting that this city represents a major segment of the             restaurant's customer base. Localized promotions in this area could yield high engagement.

  - Marital Status: The majority of customers are single, indicating a potential market for restaurants that cater to solo diners or casual social gatherings—ideal for young professionals and students.

  - Occupation & Lifestyle: A significant portion of consumers are students and non-smokers, pointing to the need for budget-friendly, youth-oriented dining experiences in a smoke-free environment.

---
### Restaurant Rating Analysis
![`Restaurant Rating Analysis`](https://github.com/Danish-ud/Restaurant-Rating-Analysis/blob/main/Rating%20analyze.png)

 - Top Performing Restaurants: The chart highlights the top 5 restaurants with the highest overall ratings, offering a benchmark for quality and customer satisfaction standards.

- Cuisine Quality vs. Popularity: Although Mexican cuisine is the most popular among consumers, its average food rating is comparatively low. This discrepancy suggests that while the demand is high, there is room for improvement in taste and quality. Enhancing flavor and consistency in Mexican dishes could significantly boost customer satisfaction.

- Smoking Preferences: Restaurants that offer a designated smoking section tend to receive higher ratings, indicating that accommodating diverse customer preferences (without compromising non-smokers' comfort) can positively influence customer experience.

- Student Demographic Ratings: The average ratings from student customers are notably lower. This may reflect unmet expectations in terms of affordability, ambiance, or service. Creating a vibrant, student-friendly environment—such as casual seating, group offers, or study-friendly spaces—can improve perception among this key segment.

- Parking Facilities Impact: Restaurants that lack parking space consistently receive lower ratings. Providing adequate parking or valet services, where feasible, would enhance customer convenience and improve overall satisfaction.

##  Key Insights

### Consumer Behavior & Demographics
- Mexican cuisine is the most preferred among consumers, but its average food rating is low — highlighting a gap between popularity and satisfaction. Improving taste and consistency can boost ratings.

- San Luis Potosí emerges as the dominant city in the dataset, offering a strong local customer base for targeted promotions.

- A significant portion of consumers are single and students, suggesting restaurants should tailor offerings and ambiance to attract younger, budget-conscious individuals.

- Most student consumers give lower average ratings, indicating a need to improve affordability, comfort, and service quality for this group.

- Non-smoking students form a large part of the customer base, reinforcing the value of a clean, smoke-free environment.

### Restaurant Features & Operational Insights
- The top 5 highest-rated restaurants set a quality benchmark — analyzing their practices can inform improvements for others.

- Restaurants with a designated smoking section receive better ratings, suggesting the value of flexible seating arrangements.

- Establishments that lack parking facilities tend to receive lower ratings. Offering parking or valet services could significantly enhance customer satisfaction.



---


