This notebook performs data cleaning, preprocessing, and feature engineering on a car dataset to prepare it for a machine learning model for car price prediction. The steps include handling missing values, extracting numerical data from text, creating new features, and encoding categorical variables.

Setup:
This project requires Python and several libraries. You can install the necessary libraries using pip:

pip install pandas numpy
Data Loading
The project expects a CSV file named train.csv to be uploaded to the Colab environment. This file contains the raw car data.

Data Preprocessing Steps
Load Data: Reads train.csv into a pandas DataFrame.
Handle Missing Values: Fills missing numerical entries with the median and missing categorical entries with the mode.
Extract Numerical Features: Extracts numerical values from 'Mileage', 'Engine', 'Power', and 'New_Price' columns.
Rename Columns: Renames 'Kilometers_Driven' to 'KM_Driven' and 'Owner_Type' to 'OwnerType'.
Feature Engineering:
Calculates 'Car_Age' from 'Year'.
Calculates 'Price_per_km' to capture price efficiency.
Calculates 'Mileage_by_Age' as a ratio of mileage to car age.
One-Hot Encoding: Converts categorical columns into numerical format using one-hot encoding.
Data Selection/Filtering: Demonstrates selecting specific columns or filtering rows based on conditions.
Sorting: Shows how to sort the DataFrame by 'Selling_Price'.
Aggregation: Calculates the mean 'Selling_Price' grouped by 'Year'.