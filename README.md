# Machine Learning Model for Predicting Customer Churn

# Predictive Data Analytics for Supermarket Sales

This repository contains a Jupyter notebook that demonstrates how to use predictive data analytics methods to analyze historical sales data from a supermarket company. The notebook includes code for data exploration, data preprocessing, and model building.

Dataset

The dataset used in this notebook is a historical sales dataset from a supermarket company. The dataset includes data on customer purchases from three different branches over a three-month period. The dataset includes the following attributes:

Invoice id: Computer generated sales slip invoice identification number.
Branch: Branch of supercenter (3 branches are available identified by A, B and C).
City: Location of supercenters.
Customer type: Type of customers, recorded by Members for customers using member card and Normal for without member card.
Gender: Gender type of customer.
Product line: General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel.
Unit price: Price of each product in $.
Quantity: Number of products purchased by customer.
Tax: 5% tax fee for customer buying.
Total: Total price including tax.
Date: Date of purchase (Record available from January 2019 to March 2019).
Time: Purchase time (10am to 9pm).
Payment: Payment used by customer for purchase (3 methods are available – Cash, Credit card and Ewallet).
COGS: Cost of goods sold.
Gross margin percentage: Gross margin percentage.
Gross income: Gross income.
Rating: Customer stratification rating on their overall shopping experience (On a scale of 1 to 10).
Notebook

The Jupyter notebook included in this repository contains the following sections:

Data exploration: This section explores the data using various visualizations, including countplots, pie charts, barplots, heatmaps, scatter plots, boxplots, and histograms.
Data preprocessing: This section preprocesses the data by removing outliers, encoding categorical variables, and scaling numerical variables.
Model building: This section builds and evaluates several machine learning models, including KNeighbors Classifier, SVC, Random Forest Classifier, Ada Boost Classifier, Gradient Boosting Classifier, DecisionTreeClassifier, GaussianNB, and Extra Trees Classifier.
Results

The results of the model evaluation show that the Random Forest Classifier and Extra Trees Classifier achieved the highest accuracy of 100%. This indicates that these models are the best at predicting sales in the supermarket company.

Conclusion

This notebook demonstrates how to use predictive data analytics methods to analyze historical sales data from a supermarket company. The results of the model evaluation show that the Random Forest Classifier and Extra Trees Classifier are the best at predicting sales in the supermarket company. These models can be used to identify trends and patterns in sales data, which can help the company to make better decisions about marketing, pricing, and inventory management.
Requirements

The following libraries are required to run the model:

Pandas
NumPy
Scikit-learn
