# Flight Price Prediction using Machine Learning

## 📌 Business Problem
Flight ticket prices vary based on multiple factors such as airline, route, duration, and timing. The goal is to predict ticket prices to help users make better booking decisions.

---

## 🎯 Project Objective
- Predict flight ticket prices  
- Identify key factors affecting pricing  
- Build regression models  

---

## 📊 Dataset
- Records: ~10,600 flights  
- Features: Airline, Source, Destination, Duration, Stops, etc.  
- Target Variable: Price  

---

## 🧠 Approach

### Data Preprocessing
- Handled missing values using mode  
- Cleaned corrupted values  
- Converted categorical features  

### Feature Engineering
- Extracted date and time features  
- Created useful predictors from duration and timing  

---

## 🤖 Models Used
- Linear Regression  
- Random Forest  
- Gradient Boosting  
- XGBoost  
- Bagging Regressor  
- SVR  

---

## 📈 Model Performance

| Model | R² Score | MAE |
|------|---------|------|
| XGBoost (Tuned) | 0.93 | 609 |
| XGBoost | 0.92 | 699 |
| Random Forest | 0.91 | 615 |
| Linear Regression | 0.67 | 1808 |

---

## 🏆 Final Model
- Selected Model: **XGBoost (Tuned)**
- Reason: Highest R² score and lowest error  

---

## 🔑 Key Insights
- Airline and route significantly affect ticket prices  
- Duration and number of stops influence pricing  
- Travel timing plays an important role  

---

## 💡 Business Impact
- Helps users estimate ticket prices  
- Supports better travel planning and decision-making  

---

## 🛠 Tech Stack
- Python (Pandas, NumPy, Scikit-learn)  
- Machine Learning (XGBoost, Random Forest, Gradient Boosting)  
- Visualization (Matplotlib, Seaborn)  

---
