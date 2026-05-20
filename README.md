# 📊 Retail Price Optimization using Machine Learning

## 🚀 Project Overview

Retail pricing plays a critical role in determining business profitability, customer demand, and market competitiveness. Traditional pricing methods are often static and fail to adapt to dynamic market behavior.

This project develops a **Machine Learning-based Retail Price Optimization System** that predicts product demand and recommends optimal prices to maximize **revenue and profit**.

The system combines:
- Predictive Modeling
- Price Elasticity Analysis
- Optimization Algorithms

to support intelligent, data-driven pricing decisions.

---

# 🎯 Problem Statement

Retail businesses face challenges such as:
- Identifying optimal product prices
- Understanding demand sensitivity (elasticity)
- Competing with dynamic competitor pricing
- Improving profitability without increasing costs

## 💡 Solution

This project solves these challenges using machine learning to:
- Predict product demand
- Analyze price elasticity
- Simulate multiple pricing scenarios
- Recommend optimal prices for maximum revenue

---

# 📁 Dataset Information

- 📦 **Total Records:** 2,400
- 🛍️ **Products:** 60
- ⏳ **Time Period:** 40 Weeks
- 📊 **Features:** 14

## 🔑 Key Features

- Product ID
- Base Price
- Selling Price
- Competitor Price
- Marketing Spend
- Inventory Level
- Promotion Type
- Season
- Day of Week
- Quantity Sold *(Target Variable)*

---

# 🧠 Machine Learning Models

| Model | R² Score |
|------|----------|
| Linear Regression | 0.8581 |
| Random Forest ⭐ | 0.8706 |

✅ **Random Forest** performed best due to its ability to capture non-linear relationships and feature interactions.

---

# ⚙️ Methodology

## 1️⃣ Data Preprocessing
- Missing value handling
- Encoding categorical variables
- Outlier analysis

## 2️⃣ Feature Engineering
Created additional business-driven features:
- Price Ratio (vs Competitor)
- Price Gap
- Price Premium
- Marketing Efficiency
- Inventory Ratio

## 3️⃣ Exploratory Data Analysis (EDA)
Performed:
- Price distribution analysis
- Demand trend analysis
- Promotion impact study
- Seasonal behavior analysis

## 4️⃣ Price Elasticity Analysis

Price elasticity measures how demand changes with price variation.

📌 **Result:**  
Average Elasticity ≈ **-0.115**

➡️ This indicates mostly **inelastic demand**, meaning demand changes only slightly with price changes.

---

## 5️⃣ Model Training

Implemented:
- Linear Regression
- Random Forest Regressor ⭐

### Evaluation Metrics
- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## 6️⃣ Price Optimization

The system:
1. Simulates multiple price points
2. Predicts demand for each price
3. Calculates expected revenue
4. Selects the optimal price maximizing revenue/profit

---

# 📈 Key Results

## 💰 Business Impact

- 📈 **Revenue Increase:** +85.65%
- 📈 **Profit Increase:** +202.08%

## 🔍 Key Insights

- Promotions are the strongest demand driver
- Competitor pricing significantly impacts sales
- Inventory levels influence demand behavior
- Most products exhibit inelastic demand

---

# 🛠️ Tech Stack

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📊 Project Workflow

```text
Data Collection
       ↓
Data Preprocessing
       ↓
Feature Engineering
       ↓
Exploratory Data Analysis
       ↓
Price Elasticity Analysis
       ↓
Model Training & Evaluation
       ↓
Price Optimization
       ↓
Business Insights & Recommendations
```

---

# 🚀 Conclusion

This project demonstrates how machine learning can transform traditional retail pricing into a **data-driven intelligent pricing system**.

By combining:
- Machine Learning Models
- Economic Concepts (Elasticity)
- Optimization Techniques

the system can significantly improve:
- Revenue
- Profitability
- Pricing efficiency
- Strategic decision-making

---

# 🔮 Future Scope

- Real-time dynamic pricing system
- Integration with competitor pricing APIs
- Advanced models (XGBoost / LightGBM)
- A/B testing in production environments
- Multi-objective optimization (Revenue + Profit + Market Share)

---

# 👨‍💻 Author

**Prudvi Pratap Kanakala**

🎓 M.Tech Data Science & Analytics Student  
🏫 Lovely Professional University

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository  
🤝 Connect with me on LinkedIn  
📢 Share your feedback and suggestions

---
