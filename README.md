🏡 London House Price Prediction (Machine Learning)

📌 Overview

This project builds a machine learning model to predict house prices in London using property and location-based features. The objective is not only to generate accurate predictions, but also to understand the key factors that drive price variation across the market.

🎯 Business Problem

Accurately pricing real estate assets is critical for buyers, sellers, investors, and financial institutions. Mispricing can lead to poor investment decisions or financial losses.


This project aims to:

Estimate property prices based on key features

Identify the main drivers of price variation

Demonstrate how data can support pricing and investment decisions


📊 Dataset

The dataset includes information on London properties, such as:

Location (borough)

Property size

Number of rooms

Other structural and geographic features

🔍 Approach

1. Exploratory Data Analysis (EDA)

Analysed price distribution across boroughs

Identified trends, correlations, and outliers

Evaluated missing values and data quality

3. Data Preprocessing

Handled missing values and inconsistencies

Encoded categorical variables

Scaled and transformed features where necessary

5. Feature Engineering

Selected key variables impacting price

Reduced noise and irrelevant features

Improved model interpretability

6. Model Development

Tested multiple machine learning models:

Linear Regression

Decision Tree

Random Forest (if applicable)

5. Model Evaluation

Models were evaluated using:

RMSE (Root Mean Squared Error)

R² Score

These metrics helped compare performance and select the most suitable model.

![Predicted vs Actual](predicted_vs_actual.png)

📈 Key Insights

Location (borough) is the strongest driver of house prices

Property size and number of rooms significantly influence valuation

Price distribution varies substantially across different areas of London

🧠 Key Learnings

Data preprocessing and feature selection are critical for model performance

Simpler models can perform well when relationships are mostly linear

Interpreting results is as important as building the model

🚀 Business Impact

This project demonstrates how machine learning can:

Support property pricing decisions

Assist in real estate investment analysis

Provide insights into market dynamics

The same approach can be applied in fintech for:

Credit risk modelling

Pricing algorithms

Customer segmentation

🛠️ Tech Stack

Python

Pandas, NumPy

Scikit-learn

Matplotlib / Seaborn

🔮 Future Improvements

Deploy the model as an API (Flask or FastAPI)

Integrate real-time property data

Incorporate external datasets (transport, crime, schools)

Improve performance using advanced models (e.g. XGBoost)


The model demonstrates strong predictive performance, with predictions closely aligned to actual values.  
Most observations cluster tightly around the diagonal, indicating good generalisation, while variance increases for high-value properties, a common pattern in real-world housing data.

