# Customer Purchase Data Analysis

## Overview
This repository contains a Jupyter Notebook (`Cust_Purch_Data_Exercise.ipynb`) that performs analysis on a dataset containing customer purchase information. The dataset includes details such as customer names, emails, phone numbers, credit card information, professions, and purchase amounts.

## Dataset Description
The dataset consists of various attributes related to customer purchases. Some key columns include:
- **first**: First name of the customer
- **last**: Last name of the customer
- **email**: Email address
- **phone**: Contact number
- **company**: Employer of the customer
- **profession**: Customer's profession
- **cc_type**: Type of credit card used
- **cc_exp**: Credit card expiration date
- **price(CAD)**: Amount spent by the customer in CAD

## Analysis Performed
The Jupyter Notebook includes several data analysis tasks, such as:
- Identifying duplicate phone numbers
- Finding customers who have not made any purchases
- Counting credit cards expiring in a specific year (e.g., 2019)
- Extracting the most popular email providers
- Filtering customers using specific email domains
- Sorting credit card types by popularity

## How to Use
1. Clone the repository:
   ```sh
   git clone <repository-url>
   ```
2. Navigate to the repository folder:
   ```sh
   cd <repository-folder>
   ```
3. Install the required dependencies:
   ```sh
   pip install pandas jupyter
   ```
4. Open the Jupyter Notebook:
   ```sh
   jupyter notebook Cust_Purch_Data_Exercise.ipynb
   ```

## Dependencies
- Python 3.x
- Pandas
- Jupyter Notebook
