# 🏘️ Real Estate Price Prediction
This project aims to predict house prices using supervised machine learning techniques. By leveraging historical property data and domain-specific feature engineering, the model provides accurate price estimates for real estate listings.


# 📌 Project Objectives 
- Predict residential property prices using Linear Regression.

- Perform in-depth EDA to uncover market patterns and trends.

- Improve model performance through data cleaning, outlier detection, and feature engineering.

- Reduce data dimensionality for optimal model efficiency.


## 📊 Dataset Overview
The dataset contains the following features:

Feature	Description
area_type : 	Type of area (e.g., Super built-up, Plot area, etc.)

availability :	Property availability status (e.g., Ready To Move, Date)

location	: Location or neighborhood of the property

size : 	Number of bedrooms (e.g., 2 BHK, 4 Bedroom)

society	: Name of the housing society

total_sqft	: Total area of the property in square feet

bath	: Number of bathrooms

balcony :	Number of balconies

price	: Selling price of the property (in lakhs)


## 🧪 Workflow Summary

Data Cleaning: Removed null values, corrected inconsistent entries, and handled categorical variables.

EDA: Analyzed price trends across locations, area types, and property sizes using visualizations.

Outlier Detection: Identified and removed extreme values in square footage and price.

Feature Engineering: Created new features such as price_per_sqft and numerical bedroom counts from size.

Dimensionality Reduction: Removed irrelevant and collinear features to improve model generalization.

Modeling: Applied Linear Regression to predict the target price with refined feature sets.


## ⚙️ Technologies Used
- Language: Python

- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

- Platform: Jupyter Notebook / Google Colab



