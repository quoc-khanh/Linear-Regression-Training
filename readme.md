# 📊 Linear Regression Training Project  

### 🚀 Analyzing Data & Implementing Tests on a Database Using Python  

📌 **SLIDE WITH SOURCE CODE** – A training session at **Vietnam National Economics University**  

---

## 🔍 Project Overview  

This project explores the application of **Linear Regression** in analyzing **e-commerce customer data** to extract meaningful insights. The goal is to determine the most significant factors influencing customer spending behavior and provide actionable recommendations for business growth.  

### 🎯 **Key Objectives**  
✅ Analyze customer data to identify influential variables  
✅ Implement **statistical tests** to validate the regression model  
✅ Compare the impact of **mobile app vs. website experience** on revenue  
✅ Provide **business recommendations** based on findings  

---

## 📂 **Dataset Overview**  
The dataset consists of **500 customer entries** from an e-commerce platform, including:  
📌 **Avg. Session Length** – Time spent per session  
📌 **Time on App** – Usage duration on the mobile app  
📌 **Time on Website** – Usage duration on the website  
📌 **Length of Membership** – Customer membership duration  
📌 **Yearly Amount Spent** – Target variable (spending behavior)  

---

## 📈 **Methodology & Analysis**  

### 🔹 **1. Data Preprocessing & Exploratory Analysis**  
- Load and clean data (drop irrelevant columns, handle missing values)  
- Visualize **distributions, outliers, and correlations**  

### 🔹 **2. Regression Analysis & Model Evaluation**  
- Perform **OLS Regression** and check statistical significance  
- Use **scatterplots, correlation matrices, and heatmaps** to analyze relationships  
- Interpret **R-squared, F-statistic, and coefficients**  

### 🔹 **3. Diagnostic Tests** (Ensuring Model Reliability)  
📌 **Multicollinearity** – Variance Inflation Factor (VIF) to detect redundant predictors  
📌 **Normality of Residuals** – Jarque-Bera test for residual distribution  
📌 **Heteroskedasticity** – Breusch-Pagan test for variance consistency  
📌 **Ramsey RESET Test** – Check for model specification errors  

---

## 🔑 **Key Findings**  

📊 **Impact of Mobile App vs. Website Usage**  
✔ **Time on App** has the **strongest positive influence** on yearly spending.  
✔ **Time on Website** shows **a weaker and even negative effect** on spending.  

📊 **Membership Duration Matters**  
✔ **Longer memberships correlate with higher spending**, indicating customer loyalty leads to revenue growth.  

📊 **Business Implications**  
✅ Prioritize **mobile app improvements** for better user engagement.  
✅ Implement **customer retention strategies** to increase membership duration.  
✅ Optimize website features but focus resources on enhancing the **mobile experience**.  

---

## 📉 **Limitations & Discussion**  
⚠ **Limited feature set** – Other factors may impact customer spending but were not included.  
⚠ **Small dataset (500 entries)** – Could lead to overfitting; results may not generalize well.  
⚠ **Multicollinearity concerns** – Some independent variables may be highly correlated.  

📌 Future work should include **larger datasets**, additional customer behavior metrics, and advanced regression techniques (e.g., **regularization methods** like Lasso/Ridge).  

---

🎤 **Presented by Group 6**  
📌 **Thank you for listening!**  

