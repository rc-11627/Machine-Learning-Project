# Machine-Learning-Project

🚗 CO₂ Emission Prediction using Regression Models

📄 Project Overview

This project predicts the CO₂ emissions of vehicles based on their engine size, fuel consumption, and other factors. Two regression models — Linear Regression and Polynomial Regression — are used to analyze the relationship between car features and emission levels.

🎯 Objective

To build and compare regression models that accurately predict CO₂ emissions and understand how polynomial features improve prediction accuracy over simple linear models.

🧠 Models Used

Linear Regression: Captures linear relationships between features and CO₂ emissions.

Polynomial Regression: Adds non-linearity to model more complex patterns in the data.

🗂️ Dataset

Dataset: Fuel Consumption and CO₂ Emission Dataset (commonly available from Kaggle
 or open government sources).

Features include:

Engine Size

Cylinders

Fuel Consumption (City/Highway/Combined)

CO₂ Emissions (Target Variable)

⚙️ Workflow

Data Cleaning & Exploration

Feature Selection

Model Training (Linear & Polynomial Regression)

Model Evaluation using R² Score and Mean Squared Error

Comparison of Results

📊 Results

Polynomial Regression showed better performance in capturing non-linear patterns compared to Linear Regression.

🧰 Tech Stack

Python

NumPy, Pandas

Matplotlib, Seaborn

Scikit-learn

📈 Future Improvements

Try Ridge/Lasso Regression for better generalization

Add more features (like vehicle type or transmission)

Deploy using Streamlit or Flask
