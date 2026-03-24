# 📊 Netflix Data Analysis Project

## 📌 Overview

This project analyzes Netflix dataset to uncover insights about content trends, genres, and country-wise distribution. The goal is to transform raw data into meaningful insights that support business decision-making.

---

## 🛠️ Tools Used

* Python (Pandas) – Data Cleaning
* Power BI – Dashboard & Visualization
* DAX – Data Analysis

---

## 🔄 Data Cleaning

* Handled missing values
* Removed duplicates
* Standardized columns
* Converted date formats

---

## 📊 Key DAX Measures

```DAX
Total Titles = COUNTROWS('Netflix')

Total Movies = 
CALCULATE(COUNTROWS('Netflix'), 'Netflix'[type] = "Movie")

Total TV Shows = 
CALCULATE(COUNTROWS('Netflix'), 'Netflix'[type] = "TV Show")

Movies % = DIVIDE([Total Movies], [Total Titles], 0)

TV Shows % = DIVIDE([Total TV Shows], [Total Titles], 0)
```

---

## 📈 Dashboard
   "C:\Users\USER\OneDrive\Pictures\Screenshots\Netflix's Dashboard picture .png"

---

## 🔍 Key Insights

* Content increased rapidly after 2015
* Movies are higher than TV Shows
* USA produces the most content
* Drama & Comedy are top genres

---

## 🚀 Conclusion

This project demonstrates end-to-end data analysis using Python and Power BI, focusing on extracting actionable insights from raw data.

---

## 📬 Contact

**Md Moeed**
📧 [mdmoeed72@gmail.com](mailto:mdmoeed72@gmail.com)
🔗 LinkedIn | GitHub
