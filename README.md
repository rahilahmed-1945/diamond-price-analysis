Diamond Price Analysis
Predicting the price of diamonds based on their physical and quality attributes using machine learning.

Project Overview:
This project builds a machine learning model to predict the price of diamonds using attributes like carat, cut, color, clarity, and more. The goal is to provide insights into which factors most influence diamond pricing and to build a model that can predict price with high accuracy.

Dataset
Source: https://drive.google.com/file/d/1I4wk5hVhl8l2Jl7sNbOq3du96CBZyTEq/view?usp=sharing

Features:
-carat (diamond weight)
-cut (quality of cut: Ideal, Premium, Good, etc.)
-colour (color grade from D to J)
-clarity (purity level)
-depth and table (dimensions)
-size (additional feature)
-price (target variable)

Technologies Used
-Python (Pandas, NumPy)
-Scikit-learn (RandomForestRegressor)
-Matplotlib & Seaborn (visualization)
-Google Colab (for coding)

Workflow
1. Upload dataset and load with Pandas
2. Preprocess categorical features using Label Encoding
3. Visualize feature relationships with heatmaps and scatter plots
4. Train/test split and model training using Random Forest
5. Evaluate model with MSE and R²
6. Plot predicted vs actual prices

Results
-The model achieved a strong R² score on the test set
-Carat was the most significant predictor of price

Files Included
1. diamond_price_analysis.ipynb — Jupyter Notebook
2. diamond_data.csv — Raw dataset 
3. README.md — This file


How to Use ?
-Clone the repo or download the files. 
-Open the .ipynb notebook in Google Colab or Jupyter and follow the step-by-step cells to reproduce the analysis.
