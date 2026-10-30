# 🚗 Car Price Prediction Using Machine Learning

## 📌 Project Overview

This project uses machine learning regression algorithms to predict the selling price of used cars based on various features, including present price, kilometers driven, fuel type, transmission, ownership history, car age, and brand.

The project demonstrates the complete machine learning workflow, from data preprocessing and feature engineering to model training, evaluation, and interactive predictions.

## 🎯 Objectives

- Predict used car selling prices using regression models.
- Perform data cleaning and preprocessing.
- Engineer meaningful features from existing data.
- Compare multiple machine learning algorithms.
- Evaluate model performance using standard regression metrics.
- Build an interactive interface for car price prediction.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- IPyWidgets

## 📊 Dataset

The dataset contains used-car information, including:

- Car name and brand
- Year of manufacture
- Present price
- Kilometers driven
- Fuel type
- Seller type
- Transmission type
- Number of previous owners
- Selling price

The target variable is `Selling_Price`, measured in lakhs.

## ⚙️ Machine Learning Workflow

1. Data loading and exploration
2. Data cleaning and handling missing values
3. Feature engineering
4. Exploratory data analysis and visualization
5. Encoding categorical variables
6. Feature scaling and preprocessing
7. Training regression models
8. Model comparison and evaluation
9. Actual versus predicted price visualization
10. Interactive car price prediction
11. Saving the trained model

## 🤖 Models Implemented

- Linear Regression
- Ridge Regression
- Random Forest Regressor
- Gradient Boosting Regressor

The best-performing model is selected based on the lowest Root Mean Squared Error (RMSE) on the test set.

## 📈 Evaluation Metrics

- **MAE:** Mean Absolute Error
- **RMSE:** Root Mean Squared Error
- **R² Score:** Coefficient of Determination

## 🚀 How to Run

1. Download or clone this repository.
2. Open `Car_Price_Prediction.ipynb` in Google Colab.
3. Upload the provided dataset ZIP file when prompted.
4. Run the notebook cells sequentially.
5. Compare the model evaluation results.
6. Use the interactive interface to predict car prices.

## 💡 Real-World Applications

- Used-car resale price estimation
- Online automobile marketplaces
- Vehicle valuation systems
- Data-driven purchasing decisions
- Automotive market analysis

## 🔮 Future Improvements

- Include horsepower, fuel efficiency, and additional vehicle specifications.
- Experiment with advanced regression algorithms.
- Perform hyperparameter tuning and cross-validation.
- Deploy the model as a web application.
- Train and evaluate the model on a larger dataset.
