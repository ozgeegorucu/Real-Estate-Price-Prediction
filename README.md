# Real-Estate-Price-Prediction
This project is a Python script that uses the scikit-learn, matplotlib, and seaborn libraries to predict house prices based on various features. The linear regression and multi regression machine learning algorithms are used for this purpose.
This project aims to predict house prices using machine learning techniques. The real estate market is a highly competitive market with various variables determining house prices. Machine learning can give effective assessments for predicting house prices, which can affect clients’ life quality and the real estate industry power. It increases the work quality of real estate agents.

# Dataset
The dataset for this project is the Real Estate.csv dataset from Kaggle Real Estate Price Prediction Dataset. The dataset consists of features in numerical data as integers and floats. There are 414 rows and a total of 8 columns in the dataset. The target column used for machine learning processes is the "Y house of unit area" column.

# EDA
Exploratory Data Analysis (EDA) was performed to understand the data. Data types, data shape and size, columns and rows, and correlation between columns were analyzed. It was found that house price of the unit area falls under the category of quantitative data type and is measurable and has an infinite number of possible values within an interval, categorized as continuous data.

# Data Preparation
The data was split into train and test sets, and feature scaling and polynomial features were applied to the data.

# Modelling
Linear regression, polynomial regression, and regulations (L1, L2, and Elastic) were applied to the data, and the models were evaluated.

# Conclusion
Residuals were analyzed, and a comparison was made between the models. The Ridge method had the minimum RMSE and maximum R2 score, indicating that it is the best model for predicting house prices.

# Results
House price of the unit area is proportional to the number of convenience stores.
House price of the unit area is inversely proportional to the distance to the nearest MRT station.
House age is not proportional to the price of unit area.
Overall, the machine learning models were able to predict house prices accurately and could be utilized in the real estate industry to facilitate quick and accurate matches between people and houses.
