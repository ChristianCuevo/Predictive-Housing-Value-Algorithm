🏠 Predictive Housing Value Algorithm
A machine learning project that predicts the average home price across U.S. counties using socioeconomic and health indicators. This end-to-end pipeline includes data wrangling, model development using linear regression, interactive visualizations, and real-time prediction capabilities.

📌 Project Overview
Objective: Estimate the average home value in a county based on its socioeconomic and health profile.

Tech Stack: Python, Scikit-learn, Pandas, NumPy, Seaborn

Model Type: Linear Regression

Test Accuracy: Achieved an R² score of 0.86

🧠 Key Features
✅ Cleaned and merged large-scale county-level datasets
✅ Built a linear regression model to predict home prices
✅ Evaluated performance using R², RMSE, and MAE
✅ Visualized predictions using color-mapped county choropleths
✅ Developed an interactive slider for real-time home value prediction based on user input

🗂️ Dataset Sources
The project integrates a variety of datasets containing:

Socioeconomic data (e.g. median income, unemployment rate, education level)

Health indicators (e.g. obesity rate, smoking prevalence, life expectancy)

Demographic metrics (e.g. population, age distribution)

All datasets were joined at the county level and underwent thorough preprocessing and feature engineering.

📊 Modeling Process
Data Preprocessing

Standardized column names and formats

Handled missing data

Merged datasets using county identifiers

Exploratory Data Analysis

Correlation heatmaps and scatterplots using Seaborn

Identified features most strongly associated with housing prices

Modeling

Trained a Linear Regression model using scikit-learn

Split data into training and testing sets (80/20)

Evaluated using:

R² Score (Coefficient of Determination)

RMSE (Root Mean Square Error)

MAE (Mean Absolute Error)

Achieved 0.86 R² score on the test set

Visualization

Generated a color-coded map of the U.S. by county to show predicted home values

Built an interactive slider UI that updates predictions in real time as users adjust key input features
