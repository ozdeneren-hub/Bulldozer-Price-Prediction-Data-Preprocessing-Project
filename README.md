🏗️ Bulldozer Price Prediction – Data Preprocessing Project
This notebook demonstrates a data preprocessing workflow in preparation for building a machine learning model to predict the sale prices of used bulldozers. The dataset comes from the Kaggle Blue Book for Bulldozers competition.

🎯 Objective
The goal of this project is to prepare a clean and well-structured dataset for machine learning. The raw dataset is enriched with engineered features, cleaned of unnecessary columns, and categorical variables are converted into numerical format.

📊 Steps Performed
Loading the dataset using pandas and parsing the saledate column as datetime

Extracting time-based features from saledate:

Sale year, month, day

Day of the year, day of the week

Converting string-based columns to categorical data types

Encoding categorical columns into numeric codes using .cat.codes

Dropping irrelevant or redundant columns (e.g., saledate)

🧰 Technologies Used
Python (pandas, numpy)

Jupyter Notebook

🔍 Dataset
Source: Kaggle - Blue Book for Bulldozers

Content: Historical auction data of used bulldozers and their sale prices

