# house-price-prediction-analysis
# 🏠 House Price Prediction Analysis

## 📌 Project Overview

This repository showcases an end-to-end **data analysis and predictive modeling project** focused on house price prediction. It highlights my proficiency in data cleaning, exploratory data analysis (EDA), and building linear regression models, tailored as part of my application for a **Data Analyst** position.

The analysis is conducted using Microsoft Excel and structured to reflect a real-world business scenario—transforming raw data into actionable insights for stakeholders.

---

## 📁 Files Included

1. **`House-pricing-raw-data.xlsx`**  
   Original dataset containing various house features and price information.

2. **`Predictive-analysis-linear-regression-model.xlsx`**  
   Cleaned and enriched dataset including:
   - Descriptive statistics  
   - Correlation analysis  
   - Simple linear regression model  
   - Multiple linear regression model  
   - Outlier treatment  
   - Missing value handling  
   - Dummy variable creation  

---

## 🔧 Key Steps in Analysis

### 1. Data Preprocessing
- **Missing Values Treatment**: Identified and filled missing data appropriately to ensure data integrity.
- **Outlier Treatment**: Handled extreme values in variables like `n_hot_rooms` and `rainfall` using capping techniques.
- **Dummy Variables**: Converted categorical variables such as `airport`, `waterbody`, and `bus_ter` into numerical format.

### 2. Exploratory Data Analysis (EDA)
- Generated summary statistics (mean, median, standard deviation)
- Visualized distributions and detected patterns
- Found key correlations, e.g., `room_num` and `price` (r = 0.696)

### 3. Regression Modeling

#### 🧮 Simple Linear Regression
- **Model**: House price ~ Number of rooms
- **Key Findings**:
  - Strong positive correlation
  - R² = 0.485 → `room_num` explains 48.5% of the price variation
  - Every additional room adds ~9.1 units to the price (p < 0.001)

#### 🧠 Multiple Linear Regression
- **Model**: House price ~ 15 features
- **Model Quality**:  
  - R² = **0.721** → Strong model fit
- **Significant Predictors** (p < 0.05):
  - `room_num` (+4.02)  
  - `air_qual` (−15.90)  
  - `teachers` (+1.01)  
  - `poor_prop` (−0.58)  
  - `n_hos_beds` (+0.33)  
  - `airport` (dummy = +1.13)  
  - Average distance to employment centers (−1.22)  

---

## 💡 Key Insights

1. **🏡 Room Number is a Major Driver**  
   More rooms = higher price. This variable alone explains nearly half the variation in house prices.

2. **📍 Location Matters**  
   - Greater distance to employment centers reduces value.  
   - More teachers likely indicate better school districts, driving up prices.

3. **🌿 Environmental Factors**  
   - Better air quality was surprisingly linked to lower prices — suggests a deeper regional factor worth exploring.

4. **🏥 Socioeconomic Indicators**  
   - More hospital beds = slightly higher prices.  
   - Higher poverty levels significantly reduce housing prices.

---

## 🛠️ Technical Skills Demonstrated

- ✅ Data cleaning & preprocessing (missing values, outliers, dummy vars)  
- ✅ Exploratory data analysis (EDA)  
- ✅ Correlation analysis  
- ✅ Regression modeling (simple & multiple linear)  
- ✅ Interpretation of coefficients & p-values  
- ✅ Insight communication with business context  

---

## 📈 How to Use This Repository

1. Start with the raw data file to understand the problem space.  
2. Explore the analysis file for the complete step-by-step modeling process.  
3. Focus on regression outputs and insights to see how variables affect house pricing.

---

## 🙋‍♂️ About Me

I’m **Max Nguyen**, an aspiring **Data Analyst** with a passion for solving problems using data. This project reflects my approach to turning data into decisions.

📧 maxnguyenhoangminh@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/max-nguyen-hoang-minh)
