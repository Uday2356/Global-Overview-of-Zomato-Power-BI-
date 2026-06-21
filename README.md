# Zomato Restaurant Analytics Dashboard

An end-to-end Power BI project analyzing 9,500+ restaurants across 15+ countries using the Zomato Restaurants dataset. The dashboard explores geographic distribution, pricing patterns, customer ratings, and cuisine trends to surface business-relevant insights for restaurant aggregator platforms.



---

##  Project Overview

This project was built as a self-directed data analysis exercise to practice the full Power BI workflow — data cleaning, modeling, DAX calculations, and dashboard storytelling — using a real-world, publicly available dataset.

The goal was to move beyond basic charting and answer real business questions, such as:
- Where are restaurants geographically concentrated, and what does that mean for market dependency?
- Does a higher price actually correlate with a higher rating?
- Which cuisines and cities represent the strongest opportunities?
- What pricing and expansion strategy would make sense given the data?

---

##  Dataset

**Source:** [Zomato Restaurants Dataset – Kaggle](https://www.kaggle.com/datasets/shrutimehta/zomato-restaurants-data)

| Detail | Value |
|---|---|
| Rows | ~9,551 restaurants |
| Countries | 15 |
| Cities | 147 |
| Key columns | Restaurant Name, City, Cuisines, Average Cost for Two, Price Range, Aggregate Rating, Votes, Latitude/Longitude |


##  Tools & Skills Used

- **Power BI Desktop** — data modeling and report design
- **Power Query** — data cleaning, column splitting (Cuisines), unpivoting, data type correction
- **DAX** — custom measures for KPIs, conditional aggregations, and filtered calculations
- **Data Visualization** — map visuals, scatter plots, matrix visuals, KPI cards


## Dashboard Pages

### 1. Global Overview
KPI cards (total restaurants, countries, cities), a geographic map visual built from latitude/longitude, and a breakdown of restaurant count by city.

### 2. Ratings & Cost Analysis
A cost-vs-rating scatter plot (bubble size = votes) to test whether higher spending correlates with better ratings, plus rating distribution and average rating by price range.

### 3. Cuisine & Location
Top cuisines by restaurant count — required splitting and unpivoting the comma-separated `Cuisines` column in Power Query — alongside locality-level drill-downs.

### 4. Country Performance Analysis :
An executive summary page translating the Restaurant count Country wise.


##  Key Findings

1. **Market concentration risk** — 90.6% of restaurants are concentrated in India, indicating strong market penetration but high geographic dependency on a single country.
2. **Rating distribution shows room for improvement** — most restaurants fall in the 3.0–4.0 range rather than the 4.0–5.0 "excellent" band, representing the largest addressable segment for service quality improvement.
3. **Cuisine preference signals demand** — North Indian is the most commonly listed cuisine, making it the strongest category for customer acquisition and partnership focus.
4. **City-level concentration** — New Delhi alone accounts for over half of all listed restaurants, representing both the highest-opportunity and highest-competition market.
5. **Pricing requires regional context** — average cost for two varies significantly by country/currency, meaning any pricing strategy must be region-specific rather than applied uniformly.

---

## ⚠️ Data Limitations

- `Average Cost for Two` is recorded in different local currencies depending on the country, so direct cross-country cost comparisons aren't statistically valid without currency normalization.
- The dataset is heavily skewed toward India (~90% of records), which limits the strength of conclusions drawn about other countries.






---

## 👤 Author
Name = Uday Pratap Verma 
Linkedin Profile = (https://www.linkedin.com/in/uday-pratap-verma-a3203a320)

Page 1 Screenshot 

<img width="1343" height="740" alt="image" src="https://github.com/user-attachments/assets/2840a49a-efc0-466f-8953-90aeb5c70cdb" />

Page 2 Screenshot :

<img width="1346" height="747" alt="image" src="https://github.com/user-attachments/assets/bb6a4fc1-501f-4443-b971-ad561017c138" />

Page 3 Screenshot :

<img width="1357" height="742" alt="image" src="https://github.com/user-attachments/assets/ccbb2adb-0115-4525-8e30-9bf5d454ecad" />

Page 4 Screenshot : 

<img width="1356" height="745" alt="image" src="https://github.com/user-attachments/assets/46270d8a-36f1-4c9e-8963-ab25a2b9f419" />







