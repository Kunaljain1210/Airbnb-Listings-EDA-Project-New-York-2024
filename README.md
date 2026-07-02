# 🏠 Airbnb Listings EDA Project – New York 2024

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **New York Airbnb Listings 2024** dataset to uncover meaningful insights about rental prices, room types, host behavior, availability, and neighborhood trends.

The analysis was carried out using **Python**, leveraging libraries such as **Pandas, NumPy, Matplotlib, Seaborn, and Plotly** for data cleaning, visualization, and analysis.

---

## 🎯 Objective

The primary objectives of this project are to:

- Analyze room types, pricing, and availability across New York neighborhoods.
- Understand host behavior and listing patterns.
- Detect and handle price outliers.
- Discover relationships between reviews, pricing, and availability.
- Provide actionable insights for Airbnb hosts and guests.

---

## 📂 Dataset Information

- **Total Records:** 20,765
- **Total Features:** 22

### Important Features

- **id** – Unique listing identifier
- **name** – Airbnb listing title
- **host_name** – Name of the host
- **neighbourhood_group** – Borough where the listing is located
- **latitude & longitude** – Geographic location
- **price** – Nightly rental price
- **room_type** – Entire Home, Private Room, Shared Room, etc.
- **reviews_per_month** – Average monthly reviews
- **availability_365** – Number of available days in a year

---

# 🛠️ Project Workflow

## 1️⃣ Data Cleaning

- Removed duplicate records.
- Handled missing values in important columns.
- Converted **last_review** to DateTime format.
- Corrected data types where necessary.
- Treated extreme price outliers to improve visualization quality.

---

## 2️⃣ Exploratory Data Analysis (EDA)

### 🛏️ Room Type Analysis

- Analyzed distribution of different room types.
- Identified **Entire Home/Apt** as the most common listing type.

### 📍 Neighborhood Analysis

- Compared listing prices across boroughs.
- Found **Manhattan** to have the highest average Airbnb prices.

### 💰 Price Distribution

- Visualized price distribution using histograms.
- Observed that most listings are priced between **$50 and $300**.

### 📅 Availability Analysis

- Studied listing availability throughout the year.
- Compared availability with pricing and reviews.

### 👤 Host Analysis

- Identified hosts managing multiple properties.
- Explored professional hosting trends.

### ⭐ Review Analysis

- Examined relationships between:
  - Price
  - Number of Reviews
  - Reviews Per Month
  - Availability

---

# 📊 Data Visualizations

The project includes various visualizations, including:

- 📈 Bar Charts
- 📊 Histograms
- 📦 Box Plots
- 🔥 Correlation Heatmap
- 📉 Pair Plot
- 📍 Scatter Plots
- 🌍 Location-based Visualizations
- 📋 Count Plots

---

# 🔍 Key Insights

## 💰 Price Trends

- Manhattan has the highest Airbnb prices.
- Brooklyn ranks second in average listing price.
- Entire homes/apartments are significantly more expensive than private or shared rooms.

---

## 🏠 Room Type Distribution

- Entire Home/Apt is the most frequently listed room type.
- Private rooms provide more affordable accommodation options.

---

## 📈 Availability Trends

- Listings with higher yearly availability generally have:
  - Lower prices
  - Higher review counts

---

## 👤 Host Behavior

- A small number of hosts manage multiple listings.
- Indicates the presence of professional Airbnb hosts.

---

## ⚠️ Price Outliers

- Some listings were priced above **$10,000** per night.
- These extreme values were treated during analysis to avoid misleading visualizations.

---

# 📚 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Understanding
- Statistical Analysis
- Business Insight Generation
- Storytelling with Data

---

# 📌 Conclusion

This project demonstrates how exploratory data analysis can transform raw Airbnb listing data into actionable business insights.

The analysis highlights pricing trends, neighborhood characteristics, host behavior, and customer preferences, enabling better decision-making for both Airbnb hosts and travelers.

---

## ⭐ If you found this project helpful, consider giving it a Star!
