# 🚴‍♂️ Exploratory Data Analysis on E-Bike 

## 📊 Project Overview

This project is a deep dive into the usage patterns of a public **E-Bike Sharing System**. By analyzing ride data, the project reveals trends in trip durations, user types, and time-based behaviors such as morning vs evening rides, weekday vs weekend activity, and more.

The goal was to clean and transform the dataset, extract useful time-based features, and visualize the insights using basic and advanced plotting techniques.

---

## 🧠 Objectives

- Understand how **user behavior** changes based on **time, day, and membership type**
- Compare **trip patterns** between **weekdays vs weekends**
- Find the **most active periods** of the day (morning, afternoon, evening, night)
- Identify which **user types (Subscriber or Customer)** use the service more frequently
- Present all findings using **basic yet powerful visualizations**

---

## 🗂️ Dataset Description

The dataset includes:

- `starttime`: The start time of each trip  
- `stoptime`: The end time of each trip  
- `tripduration`: Duration of each trip (in seconds)  
- `usertype`: Subscriber or Customer  
- `MEMBERSHIP_TYPE`: Membership category  
- Other metadata like station names, locations, etc.

---

## 🛠️ Tools & Libraries Used

- **Python**
- **Pandas** – for data cleaning and manipulation
- **Matplotlib** – for creating basic plots
- **Seaborn** – for advanced plots like boxplot, violinplot, etc.
- **Jupyter Notebook / Google Colab** – for interactive analysis

---

## 🔧 Data Preprocessing & Feature Engineering

The raw data was enhanced by creating several new columns:

| Feature | Description |
|--------|-------------|
| `tripduration_mins` | Converted from seconds to minutes (rounded to 2 decimals) |
| `month`, `year`, `day_name` | Extracted from `starttime` |
| `hour` | Extracted to help group trips by time of day |
| `time_of_day` | Categorized as 'Morning', 'Afternoon', 'Evening', or 'Night' |
| `TYPE_OF_WEEK` | Marked as 'Weekday' or 'Weekend' based on `day_name` |

---

## 📈 Visualizations

Here are some of the key visualizations created:

- 📊 **Bar Charts** – Comparing total trips and average duration between weekdays and weekends
- 🎯 **Scatter Plots** – Visualizing trends between different variables
- 📦 **Box Plots** – Showing spread of trip duration across user types
- 🎻 **Violin Plots** – Visualizing trip duration distributions in a more intuitive way
- 🟰 **Time-based plots** – Analyzing usage trends across different hours and days

All graphs are created using **very basic syntax** — perfect for beginners in data analysis.

---

## 📌 Key Findings

- **Subscribers take more trips** compared to Customers, especially on **weekdays**
- **Customers ride longer trips** on average than Subscribers
- Most trips happen during the **morning and evening**—typical commute times
- The **weekend** has fewer trips, but the **average duration is longer**
- Majority of users prefer E-Bikes during **weekday mornings**

---

## ✅ Conclusion

This EDA project shows how simple data transformations and visualizations can uncover **powerful insights** from even basic bike-sharing data. By categorizing time, cleaning duration values, and comparing user types, the analysis paints a clear picture of user behavior.

This project can serve as a great starting point for further analysis or building predictive models (e.g., predicting trip duration or peak times).

---

## 👤 Author

**Affaan Waghoo**  
🔗 [LinkedIn: www.linkedin.com/in/affaanwaghoo09112004](https://www.linkedin.com/in/affaanwaghoo09112004)
