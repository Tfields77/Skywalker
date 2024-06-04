# Skywalker
Skywalker, a comprehensive data cleaning tool, preprocesses and cleans datasets. It handles tasks like removing null values, converting data types, filling missing values, and standardizing formats. Named after Star Wars characters, each method reflects its functionality, making it easy to remember and use.
# Skywalker Data Cleaning Tool

## Overview

Skywalker is a comprehensive data cleaning tool designed to preprocess and clean datasets. It handles various tasks such as removing null values, converting data types, filling missing values, standardizing formats, and more. This tool is named after characters from the Star Wars universe, with each method named after a character to indicate its functionality.

## Features

- Remove null values
- Convert string numbers to integers
- Fill blank spaces in specific columns
- Handle outliers
- Standardize text formats
- Remove duplicates
- Normalize data
- Encode categorical variables
- Impute missing values using KNN
- Remove unwanted characters
- Bin numerical data
- Strip whitespace from strings

## Installation

To use the Skywalker tool, you need to have Python and the following libraries installed:
- pandas
- scikit-learn

You can install these libraries using pip:

pip install pandas scikit-learn
Usage
Step 1: Save the Skywalker Tool
Save the following code as skywalker.py:
Method Descriptions
What Each Character Does
Han Solo: Removes null values from the dataset.
Leia Organa: Converts string numbers to integers where applicable.
Ben Solo: Fills blank spaces in the 'year' column using forward fill and backward fill methods.
Luke Skywalker: Fills missing numerical values with the mean of the column.
Jaina Solo: Handles outliers by capping them within the interquartile range (IQR).
Shmi Skywalker: Standardizes text formats by stripping whitespace and converting to lowercase.
Jacen Solo: Removes duplicate rows from the dataset.
Anakin Solo: Normalizes numerical data using standard scaling.
Padme Skywalker: Encodes categorical variables using one-hot encoding.
Obi-Wan Skywalker: Imputes missing values using the K-Nearest Neighbors (KNN) algorithm.
Rey Skywalker: Removes unwanted characters such as dollar signs and commas.
Kylo Ren: Bins numerical data into quartiles.
Anakin Skywalker: Strips whitespace from strings in the dataset.
By following these steps and using the described methods, you can effectively clean and preprocess your datasets using the Skywalker Data Cleaning Tool.
