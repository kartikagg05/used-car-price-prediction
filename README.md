# Used Car Price Prediction
This project aims to predict the prices of used cars based on various features such as the car's make, model, age, mileage, fuel type, and more. The dataset used for this project is obtained from a publicly available source and contains information about used cars in India.
# Dataset
The dataset consists of two files:

train-data.csv: Contains the training data with 6,019 instances and 14 features.
test-data.csv: Contains the test data with 1,234 instances and 13 features.

# Data Preprocessing
The data preprocessing steps involved in this project include:

Handling missing values by dropping rows with null values in certain crucial features.
Converting categorical features into numerical form using techniques like one-hot encoding and label encoding.
Feature engineering by extracting additional features from existing ones (e.g., splitting 'Mileage' into 'Mileage(km/kg)').
Removing unnecessary features.

# Exploratory Data Analysis
Exploratory data analysis was performed using various visualization techniques, including histograms, box plots, swarm plots, and heatmaps. These visualizations provided insights into the distribution of the target variable (Price) and the relationship between different features and the target variable.
# Feature Selection
The Extra Trees Regressor algorithm was used for feature selection, which helped identify the most important features influencing the used car prices.
# Model Building
Two regression models were trained and evaluated:

Linear Regression
Random Forest Regression

The Random Forest Regression model performed significantly better than the Linear Regression model, achieving an R-squared score of 0.9055 on the test set.
# Usage
To run the code and make predictions, follow these steps:

Clone the repository or download the source code.
Install the required dependencies (e.g., NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn).
Run the code, and the trained Random Forest Regression model will be used to make predictions on the test data.
