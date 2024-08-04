# Sales Orders Data Analysis Project

## Overview

This project focuses on the analysis of a sales orders dataset using Python and SQL. The dataset includes comprehensive details about orders such as order dates, shipping modes, customer segments, product categories, prices, and discounts. The analysis involves data cleaning, preprocessing, and calculation of key metrics like sale prices and profits. The processed data is then stored in a MySQL database for further analysis and use.

## Dataset

The dataset (`orders.csv`) contains the following columns:
- **Order Id**: Unique identifier for each order
- **Order Date**: Date when the order was placed
- **Ship Mode**: Shipping mode (e.g., Second Class, Standard Class)
- **Segment**: Segment of the customer (e.g., Consumer, Corporate)
- **Country**: Country of the customer
- **City**: City of the customer
- **State**: State of the customer
- **Postal Code**: Postal code of the customer
- **Region**: Region of the customer
- **Category**: Product category (e.g., Furniture, Office Supplies)
- **Sub Category**: Product sub-category (e.g., Bookcases, Chairs)
- **Product Id**: Unique identifier for each product
- **Cost Price**: Cost price of the product
- **List Price**: List price of the product
- **Quantity**: Quantity of the product ordered
- **Discount Percent**: Discount percentage applied to the order

## Project Structure

The project consists of the following key steps:

1. **Data Loading and Initial Exploration**
    - Load the dataset into a pandas DataFrame.
    - Perform initial exploration to understand the structure and content of the data.

2. **Data Cleaning and Preprocessing**
    - Handle missing values.
    - Convert data types as necessary.
    - Calculate additional columns such as discount amount, sale price, and profit.

3. **Data Visualization**
    - Generate visualizations to gain insights into the data.

4. **Database Integration**
    - Connect to a MySQL database using SQLAlchemy.
    - Store the processed data in the database for further analysis.

## Requirements

The project requires the following Python libraries:
- pandas
- matplotlib
- seaborn
- numpy
- sqlalchemy
- pymysql

  You can install the required libraries using the following command:
  ```sh
    pip install pandas matplotlib seaborn numpy sqlalchemy pymysql
## Setup and Usage

1. Clone the repository:
    ```sh
    git clone https://github.com/shreyash4Z/Sales-Order-Analysis
    cd sales-orders-data-analysis
    ```

2. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Run the Jupyter Notebook:
    Open the Jupyter Notebook and execute the cells to run the analysis.

4. Database Configuration:
    Ensure you have a MySQL server running and update the connection details in the notebook accordingly.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.
