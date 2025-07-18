# Canadian Housing Price Prediction using Machine Learning

This project was developed for the ECE 470/569A Artificial Intelligence course at the University of Victoria (Summer 2025). It explores the use of machine learning models to predict house prices across major Canadian cities using a real-world dataset.

## Project Objective
To build a predictive model that estimates house prices based on geographic location (city, province), number of bedrooms and bathrooms, and latitude. The project also compares model performance and interprets geographic trends in pricing.

## Repository Structure
- `eda_analysis.ipynb`: Initial exploratory data analysis (EDA) and insights about the dataset.
- `data_Preprocessing.ipynb`: Data cleaning, feature engineering, and one-hot encoding.
- `modeling_linear_regression-XGBoost.ipynb`: One-hot encoding, baseline model using Linear Regression, comparison with XGBoost, visualization, and simulation results.

## Models Compared
- **Linear Regression** (Baseline)
- **XGBoost Regressor** (Advanced)

XGBoost outperforms the baseline model with better generalization and lower prediction error.

## Key Features
- Predictive simulation for custom user input.
- Price comparison across provinces (Toronto, Vancouver, Calgary).
- Visual diagnostics (scatter plot & residuals) for both models.

## Dataset
The dataset includes over 30,000 house listings across Canada, with city, province, number of beds/baths, price, and coordinates. Sourced from Kaggle.

## Technologies Used
- Python 3.10
- Pandas, NumPy, scikit-learn, XGBoost, Matplotlib
- Jupyter Notebooks

---

University of Victoria | ECE 569A – Artificial Intelligence course Project | Summer 2025
