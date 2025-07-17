# 🌾 Crop Yield Prediction using Machine Learning

This project aims to predict agricultural crop production using machine learning models based on features like location, crop type, area, and season. The dataset has been preprocessed and several models have been evaluated for their performance.

---

## 📁 Dataset

- Source: [Your data source, if any]
- Columns: `State_Name`, `District_Name`, `Crop_Year`, `Season`, `Crop`, `Area`, `Production`
- Target Variable: `Production`

---

## 🧹 Preprocessing Steps

- Removed missing/null values
- One-hot encoded categorical variables (`State_Name`, `District_Name`, `Season`, `Crop`)
- Normalized features where required
- Split data into training and testing sets (80:20)

---

## 🤖 Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

---

## 📊 Evaluation Metrics

Each model was evaluated using the following metrics:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

---

## 🏁 Results

| Model                  | R² Score | MAE     | MSE      |
|------------------------|----------|---------|----------|
| Linear Regression      | x.xxx    | x.xxx   | x.xxx    |
| Decision Tree          | x.xxx    | x.xxx   | x.xxx    |
| Random Forest          | x.xxx    | x.xxx   | x.xxx    |
| Gradient Boosting      | x.xxx    | x.xxx   | x.xxx    |

> *(Replace the `x.xxx` values with actual results after running the code)*

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
