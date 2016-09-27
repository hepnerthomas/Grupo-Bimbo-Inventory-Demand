Grupo Bimbo Inventory Demand
----------------------------

This repository contains my project code and project report for the Grupo Bimbo Inventory Demand Kaggle competition. The goal of the project was to develop a model that could most accurately forecast inventory demand for Grupo Bimbo products baed on historical sales data.

Competition Information and Data
--------------------------------
All information and data can be obtained from the competition web page: 
https://www.kaggle.com/c/grupo-bimbo-inventory-demand

iPython Notebooks
-----------------
1. exploratory analysis: 

* Explores product and client data.
* Discovers new features that can be generated from NombreProducto and NombreCliente variables.

2. feature engineering:

* Takes the findings from the exploratory analysis and creates new product and client data sets with additional features.

3. build:
* Load train, test, and modified client and products data.
* Merges modified client and products data into train and test data.
* Adds time series demand features.
* Adds mean of frequencies of id features.
* Encodes categorical variables.
* Removes data before Week 6.
* Writes modified train and test data to CSV.

4. predict: 
* Fits an XGBOOST model to the train data.
* Validate model results on a held-out subset of the train data.
* Generates results for the test data.

5. free-form-visualization:
* Uses Matplotlib to plot weekly sales of the top 4 best-selling products in the train data. 

Project Report
--------------

This is the PDF report for the Machine Learning Engineer Capstone project. It details the process I implemented, the analyses performed, and the models built to solve the goal of the Grupo Bimbo competition.

References and Sources
-----------------------
1. XGBOOST: https://github.com/dmlc/xgboost

2. Sklearn: http://scikit-learn.org/stable/

3. Owen Zhang's Tips for Data Science Competitions: http://www.slideshare.net/OwenZhang2/tips-for-data-science-competitions

4. Classifying Client Type using Client Names: https://www.kaggle.com/abbysobh/grupo-bimbo-inventory-demand/classifying-client-type-using-client-names

5. Exploring Products: https://www.kaggle.com/vykhand/grupo-bimbo-inventory-demand/exploring-products


