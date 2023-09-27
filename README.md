# Flight Delay Prediction Project
## Overview
This project is dedicated to predicting flight delays based on data related to flights in the United States during the year 2015. We've undertaken two primary tasks in this project: regression prediction of ARRIVAL_DELAY and classification prediction of ARRIVAL_DELAY (True/False).

We will meticulously clean and preprocess the dataset to ensure it meets the requirements of both tasks. Additionally, we will apply a variety of regression and classification models, assessing their performance for each prediction type.

## Project Goals
The key objectives of this project encompass:

Building an accurate machine learning model for regression, specifically for predicting ARRIVAL_DELAY based on flight-related features.
Developing a robust classification model to predict whether a flight will experience a delay (ARRIVAL_DELAY) or not.
Gaining hands-on experience in data preprocessing, feature engineering, and modeling within the field of data science and machine learning.
## Main Features
Our project encompasses the following key components:

Data Preprocessing: We perform comprehensive data cleaning to address missing values and outliers, ensuring data quality for both regression and classification tasks.
Feature Engineering: We engage in feature engineering to create new attributes and transform existing ones, thereby enhancing the predictive power of our models.
Regression Models: For predicting ARRIVAL_DELAY, we implement various regression models, including, but not limited to:
Linear Regression
Decision Trees Regression
xgboost Regressor
Classification Models: To classify flights as delayed or not, we explore classification models such as Logistic Regression, Decision Trees, and Random Forest Classification.
## Technologies Used
This project utilizes several key libraries and technologies:

Python: We use Python as the primary programming language for data analysis and modeling.
pandas: pandas library is used for data manipulation and analysis.
numpy: numpy is employed for numerical computations.
scikit-learn (sklearn): scikit-learn is used for implementing machine learning algorithms.
optuna: optuna is used for hyperparameter optimization.
cartopy: cartopy is utilized for geospatial data visualization.
matplotlib: matplotlib is used for creating plots and visualizations.
scipy: scipy is used for scientific and statistical computations.
xgboost etc.
## Installation Instructions
To run this project locally, follow these steps:

Clone the repository: git clone 'https://github.com/kriskalb/flight-delay-prediction'
Navigate to the project directory: cd flight-delay-prediction
Install the required Python packages: pip install -r requirements.txt
Run the Jupyter Notebook or Python script to train and test the models.
Download datasets from https://www.kaggle.com/code/abhishek211119/2015-flight-delays-and-cancellation-prediction
Datasets are too large to share in github.

It is recommended to run the project in Google Colab
## Authors
kriskalb
## License
This project is open-source.

Feel free to replace "kriskalb" in the Authors section with your name or the names of any collaborators. You can also replace the GitHub repository URL with your project's URL.
