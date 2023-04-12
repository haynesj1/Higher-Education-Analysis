# Higher-Education-Analysis
This project aims to analyze higher education data, focusing on institutions and courses. The code processes, analyzes, and visualizes various features to provide insights into the performance of the institutions and their courses. These insights can be used for decision-making and policy development in the higher education sector.

Dependencies
pandas
numpy
seaborn
matplotlib
scikit-learn
statsmodels
Usage
Import the necessary libraries and load the data from CSV files.

Preprocess the data by handling missing values, dropping unnecessary columns, and merging relevant data from different files.

Perform one-hot encoding on categorical features like 'LEGAL_NAME' for further analysis and modeling.

Apply linear regression on selected features to predict the median salary of graduates ('GOINSTMED') and calculate performance metrics such as R-squared value, mean squared error, mean absolute error, and explained variance score.

Calculate the correlation matrix for the selected features to analyze the relationships between them.

Calculate the median tariff points for different course levels and obtain a weighted tariff for each level. Calculate the sum of the weighted tariffs for each institution to get the average tariff points.
