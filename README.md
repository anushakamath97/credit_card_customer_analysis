# credit_card_customer_analysis

The project analyses credit card customers data of a bank and help predict which customer might close their  account using some visualisations and supervised ML algorithms.

## Installations

Analysis was done using [google colab notebook](https://colab.research.google.com/).
All the packages used in the iPython Notebook are installed by default in colab.

The versions used while writing the code are mentioned below.

* `pandas==1.1.5`
* `numpy==1.19.5`
* `matplotlib==3.2.2`
* `seaborn==0.11.1`
* `sklearn==0.0`

## Motivation

A bank is having a problem identifying the customers who might be unhappy with the credit card services. The project goal is the build a supervised machine learning model to predict any customer who might be closing their account.

The data analysis tries to answer the following questions from the dataset, which can help the bank to focus of customers who they can easily persuade to change their decision of leaving.

* How many customers are highly educated?
* Do highly educated people have high income?
* Is spending trend consistent with Income.
* Is age a factore for more credit card usage?

## File Descriptions and Usage

- BankChurners.csv: This file has the data obtained from [Kaggle](https://www.kaggle.com/sakshigoyal7/credit-card-customers)

- Credit Card Customer.ipynb: Contains the full code for data analysis and prediction.

Clone the repository to your machine, in [colab](https://colab.research.google.com/) go to File -> Open notebook -> Upload. Select the ipynb file.

Once the notebook opens, create a **sample_data** folder in the Files section of notebook. Upload the BankChurners.csv file to sample_data folder.