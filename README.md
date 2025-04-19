# 🚗 Car Price Prediction using Linear Regression

This project implements a **Car Price Prediction Model** using **Linear Regression**. The goal is to predict the selling price of cars based on features such as year, kilometers driven, fuel type, transmission, and others.

---

## 🚀 Features

- Data preprocessing using one-hot encoding to handle categorical variables
- Linear regression model to predict car selling prices
- Evaluation using **Mean Squared Error (MSE)** and **R^2 Score**
- Visualization of predicted vs actual prices

---

## 🧠 Algorithms Used

- **Data Preprocessing:** One-hot encoding of categorical features using `get_dummies`
- **Model:** Linear Regression

---

## 📦 Dependencies
pip install pandas scikit-learn matplotlib seaborn

---

## 📊 Performance
The model achieves an R^2 Score of 0.60 and a Mean Squared Error (MSE) of 121,717,437,561.63 on the test data.

R^2 Score: 0.601

Mean Squared Error (MSE): 121,717,437,561.63

This indicates that the model explains approximately 60% of the variance in the car prices.

---

## Visualization
The scatter plot below shows the comparison between actual and predicted prices. The red dashed line represents a perfect prediction (where predicted prices equal actual prices).

---

## 📌 Conclusion
The project demonstrates how to predict car selling prices based on multiple features using Linear Regression. Despite the moderate R^2 score, the model provides reasonable predictions and can be further optimized with feature engineering and more advanced models.

---

## 📃 License
This project is open-source and available under the MIT License. You are free to use  and modify.



