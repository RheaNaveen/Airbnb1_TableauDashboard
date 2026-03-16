# Airbnb Listings 2016 – Data Analysis Dashboard (Tableau)

This project analyzes Airbnb listing data to understand pricing trends, geographic distribution of listings, demand patterns, and market competition among different property types.

The dashboard was created using Tableau to transform raw Airbnb data into meaningful visual insights that help understand how the short-term rental market behaves.

---

## Dashboard Preview

Dashboard Preview([Airbnb dashboard image.png](https://github.com/RheaNaveen/Airbnb1_TableauDashboard/blob/main/Airbnb%20dashboard%20image.png))

---

## Project Objective

The goal of this project is to explore Airbnb listing data and identify patterns related to pricing, location, demand, and competition. By visualizing the dataset, this dashboard helps answer important questions such as:

- Which locations are considered premium for Airbnb listings?
- How does pricing change with different bedroom types?
- When does Airbnb demand peak during the year?
- How competitive is the market for different property types?

This project demonstrates how data visualization can convert raw data into insights that support better decision-making for hosts, investors, and analysts.

---

## Dataset

Dataset Name: **Airbnb Listings 2016 Dataset**

Source: Kaggle  

Dataset Link:  
https://www.kaggle.com/datasets/alexanderfreberg/airbnb-listings-2016-dataset

The dataset contains Airbnb listing data from 2016 including information about price, bedrooms, zipcode, listing availability, and booking calendar data used to analyze revenue trends. :contentReference[oaicite:0]{index=0}

Due to file size limitations, the dataset file is not included in this repository.

---

## Tools Used

- Tableau
- Data Visualization
- Exploratory Data Analysis
- Kaggle Dataset

---

## Dashboard Components

### 1. Price by Zipcode

This bar chart compares the **average Airbnb price across different zipcodes**.

Purpose:
- Identify premium or expensive locations
- Compare price differences between neighborhoods
- Understand how location affects Airbnb pricing

This helps highlight which areas have the highest market value.

---

### 2. Geographic Distribution of Listings

The map visualization shows **where each zipcode is located geographically**.

Purpose:
- Provide spatial context to the pricing data
- Visualize where high-price and low-price listings are located
- Identify clusters of expensive areas

This allows users to easily connect price differences to real locations.

---

### 3. Revenue Trend Over Time

The line chart shows **revenue patterns throughout the year**.

Purpose:
- Identify peak periods when Airbnb demand increases
- Understand seasonal booking trends
- Observe how revenue changes during the year

This insight can help hosts optimize pricing strategies during high demand periods.

---

### 4. Bedroom Type vs Average Price

This visualization compares the **average price of listings based on the number of bedrooms**.

Purpose:
- Understand how property size affects pricing
- Identify which bedroom types generate higher prices
- Evaluate the performance of larger properties

The analysis shows that listings with more bedrooms generally command higher prices.

---

### 5. Competition Analysis (Distinct Count of Listings)

This section analyzes **how many listings exist for each bedroom type**.

Purpose:
- Measure market competition
- Identify which property types dominate the market
- Understand the supply distribution across listings

For example, one-bedroom listings appear most frequently, indicating higher competition.

---

## Key Insights

- Some zipcodes consistently show higher Airbnb prices, indicating premium locations.
- Larger properties with more bedrooms generally achieve higher average prices.
- One-bedroom listings dominate the market in terms of supply.
- Revenue trends reveal peak periods of Airbnb activity during the year.
- Geographic analysis helps identify potential high-value investment areas.

---

## Repository Structure

```
Airbnb-Tableau-Dashboard
│
├── dashboard.twbx
├── dashboard_preview.png
└── README.md
```

## Design Approach

A consistent blue color palette was used across the dashboard to maintain a professional look and improve visual clarity. Using a single color theme reduces visual clutter and helps users focus on the insights presented in the charts.
