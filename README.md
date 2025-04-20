# 🎢 Roller Coaster EDA | Kaggle Dataset

This project performs an **Exploratory Data Analysis (EDA)** on a dataset of roller coasters collected from **Kaggle**. The goal is to explore key trends, identify patterns, and gain insights into roller coaster characteristics across different locations and years.

---

## 📁 Dataset Overview
- Source: Kaggle (Roller Coaster Database)
- Records: 1087 roller coasters
- Features: 56 (after cleaning: 13 main columns used)
- Includes: Name, Location, Year Introduced, Speed, Height, G-force, Type, and more.

---

## 📊 Analysis Highlights

### 🧼 Data Preparation
- Dropped unnecessary columns
- Converted date formats
- Renamed columns for clarity
- Removed duplicate entries using key columns like `Coaster_Name`, `Location`, and `Opening_Date`

### 📈 Univariate Analysis
- Distribution of coaster speeds (`Speed_Mph`) using histograms and KDE
- G-force distribution (`Gforce`)
- Number of coasters introduced by year (`Year_Introduced`)
- Count of coaster types (`Type_Main`)

### 🧩 Multivariate Relationships
- Scatter plots: Speed vs. Height
- Pairplots: `Speed`, `Height`, `Inversions`, `Gforce`, and `Year_Introduced`
- Heatmap: Feature correlation matrix
- Groupby visual: Average speed by `Location` (only where ≥10 coasters)

---

## 📌 Tools Used
- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Google Colab**

---

## 📎 What You Can Learn
- How to clean and prepare real-world messy data
- Techniques to detect and remove duplicates
- Visual exploration of numeric and categorical features
- Finding trends like:
  - What years had the most coaster releases
  - Which coaster types are most common
  - Which locations have the fastest coasters

---

## 🚀 Project Status
✅ Complete – ready to showcase  
🔜 Future Ideas: Add clustering, feature engineering, or build a dashboard with Plotly or Streamlit.

---


**Thisura**  
*Postgraduate Diploma in Data Science, Manipal Dubai*

Connect with me on [LinkedIn]([https://www.linkedin.com/in/thisura-raksitha/]) 


