# 🚗 Car Price Prediction using Machine Learning

This project focuses on predicting the resale value of cars based on several features like manufacturing year, current price, mileage, fuel type, and transmission. It utilizes regression algorithms to provide accurate price estimations.

## 📌 Project Overview
Determining the accurate market value of a used vehicle is essential for both buyers and sellers. This project implements and compares two different regression algorithms: **Linear Regression** and **Lasso Regression**, to find the most effective model for this dataset.

## 📊 Technologies & Libraries
The following Python libraries were used in this project:
* **Pandas**: For data manipulation, cleaning, and label encoding.
* **Matplotlib & Seaborn**: For data visualization and plotting Actual vs. Predicted values.
* **Scikit-learn**: For data splitting, implementing regression models, and evaluation.

## 🛠️ Workflow
1. **Data Preprocessing**: Categorical features like `Fuel_Type`, `Seller_Type`, and `Transmission` were converted into numerical values (Encoding).
2. **Data Splitting**: The dataset was divided into Training (90%) and Testing (10%) sets.
3. **Model Training**: Both Linear Regression and Lasso Regression models were trained on the data.
4. **Evaluation**: Model performance was measured using the **R-squared ($R^2$)** error metric.

## 📈 Results and Comparison
The performance of the models based on the $R^2$ score:

| Algorithm | Training Accuracy ($R^2$) | Test Accuracy ($R^2$) |
| :--- | :--- | :--- |
| **Linear Regression** | 0.8799 | 0.8365 |
| **Lasso Regression** | 0.8427 | **0.8709** |

**Observation:** The **Lasso Regression** model performed better on the test data, showing better generalization capabilities.



## 🚀 How to Run
1. Clone this repository to your local machine.
2. Ensure you have the dataset `car data.csv` in the project folder.
3. Open the `.ipynb` file in Google Colab or Jupyter Notebook.
4. Run all cells to see the analysis and predictions.
