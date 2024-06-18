# Store Sales Time Series Forecasting
Project Overview
This project aims to forecast daily sales for multiple stores using historical sales data. The goal is to build predictive models that can accurately estimate future sales, aiding in inventory management, staffing, and other operational decisions.

Dataset

The dataset used for this project is the "Store Sales - Time Series Forecasting" dataset available on Kaggle. It contains historical sales data for various stores and items.

Files

train.csv: Training data with sales information.

test.csv: Test data without sales information (target variable).

sample_submission.csv: Sample submission file in the correct 
format.

stores.csv: Metadata about the stores.

transactions.csv: Daily number of transactions for each store.

Columns in train.csv

id: Unique identifier for the record.

date: Date of the sale.

store_nbr: Store number.

item_nbr: Item number.

unit_sales: Number of units sold (target variable).

onpromotion: Indicates if the item was on promotion on that day.

Usage

Data Preprocessing

Load Data: Load the training and additional datasets.

Merge Data: Combine datasets to enrich the training data.

Handle Missing Values: Impute or remove missing values as necessary.

Feature Engineering: Create new features such as lag features, moving averages, and time-based features (e.g., day of week, month).

Exploratory Data Analysis (EDA)

Understand the distribution of sales.

Identify trends, seasonality, and outliers.

Analyze the impact of promotions, holidays, and oil prices on sales.

Modeling

Train-Test Split: Split the data into training and validation sets.

Baseline Model: Start with a simple model like Naive Forecast or Mean Forecast.
