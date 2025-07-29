This code performs data analysis and machine learning modeling on a dataset of video game sales. The goal is to explore global sales trends and build a predictive model for estimating global game sales based on various features.

📂 Dataset
The dataset contains sales figures for various video games across different platforms and regions. Features include:

Name

Platform

Year of Release

Genre

Publisher

Sales by region (NA, EU, JP, Other)

Global Sales

📊 Exploratory Data Analysis (EDA)
We conduct thorough EDA using pandas, matplotlib, and seaborn, including:

📌 Bar chart of global sales by genre

📌 Heatmap of sales by genre and platform

📌 Pie chart showing regional sales distribution

📌 Top 10 publishers by global sales

🤖 Machine Learning Model
We use a Random Forest Regressor to predict the Global_Sales target variable.

Steps:
Data Preprocessing

Dropped unnecessary columns

Encoded categorical features using one-hot encoding

Feature Selection

Selected Platform, Genre, Publisher, and Year as features

Modeling

Train/Test split (80/20)

5-Fold Cross-validation

Model evaluation using:

R² Score

Mean Squared Error (MSE)

🔁 Cloning the Repository:
git clone https://github.com/Mohamed-Kenawy/Video_Game_Sales_predictor.git
