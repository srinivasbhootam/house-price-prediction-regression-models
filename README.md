
# 🏠 House Price Prediction using Regression Models

This repository contains a comprehensive machine learning project focused on predicting residential property prices using multiple regression techniques. The project was developed as part of an academic lab for a machine learning course in the MSBA program.

---

## 📌 Objective

The primary goal is to predict house prices based on various structured property features using three regression models:

- **Linear Regression**
- **Ridge Regression**
- **Polynomial Regression (Degree 2)**

The models are evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)


---

## 🧠 Dataset Description

The dataset contains over 93,000 residential property records with features such as:

- Carpet Area
- Property Status
- Floor Information
- Transaction Type
- Furnishing Status
- Facing and Overlooking
- Bathroom, Balcony, Car Parking Count
- Ownership Type
- Super Area / Plot Area / Dimensions
- Price and Location

---

## 🔍 Exploratory Data Analysis (EDA)

Visualizations included:
- Price distribution
- Carpet Area vs. Price
- Bathroom Count vs. Price
- Correlation heatmap for numerical features

EDA insights revealed that **Carpet Area** and **Bathroom Count** have a weak positive correlation with price, while other features showed low individual correlation.

---

## 🤖 Models & Evaluation

Three models were implemented and tested:

| Model                         | MAE      | MSE            | RMSE     |
|------------------------------|----------|----------------|----------|
| Linear Regression            | 2,699.39 | 886,907,481.35 | 29,780.99 |
| Ridge Regression             | 2,681.37 | 885,889,993.86 | 29,763.90 |
| Polynomial Regression (D2)   | 2,235.81 | 3,918,571,158.96 | 62,598.49 |

> **Conclusion**: WWhile Polynomial Regression (Degree 2) achieved the lowest Mean Absolute Error (MAE), it also resulted in a significantly higher Root Mean Squared Error (RMSE) and Mean Squared Error (MSE). This indicates that although the model made some accurate predictions, it also produced large errors on certain data points — a classic sign of overfitting.

In contrast, Ridge Regression demonstrated a more balanced performance across all evaluation metrics. Its incorporation of L2 regularization helped control model complexity, reduced overfitting, and delivered consistent predictions across the dataset.

👉 Therefore, Ridge Regression is the recommended model for this housing price prediction task due to its stability, robustness, and overall generalization capability.

---

## 🛠️ Technologies Used

- Python 3.11
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn (Linear, Ridge, Polynomial Regression)
- Google Colab

---

## 📄 Lab Report

The complete report is available in House Price Prediction using Regression Models File. It includes:

- Abstract & Objective
- Literature Review
- Methodology
- Model Evaluation & Discussion
- References

---

## 🧾 References

- Kumar, R., & Garg, A. (2020). *Comparative study of regression techniques for house price prediction*. International Journal of Computer Applications, 175(7), 1-5.
- Wang, J., Liu, Y., & Zhao, H. (2021). *Improving house price prediction accuracy through feature engineering and machine learning*. Procedia Computer Science, 183, 271-278.
- Scikit-learn Developers. (2023). *Scikit-learn: Machine Learning in Python*. https://scikit-learn.org/

---

## ✍️ Author

**Srinivas Bhootam [MSBA 2025 Candidate]**  
This project was developed as part of a machine learning lab assignment to gain practical experience in predictive modeling and performance evaluation using real-world data.

---

## 📬 Contact

For collaboration:  
📧 srinivas.bhootam@gmail.com
🔗 https://www.linkedin.com/in/bhootam-srinivas/

---


