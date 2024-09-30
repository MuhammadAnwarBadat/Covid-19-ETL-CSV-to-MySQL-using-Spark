
# COVID-19 ETL Process Using Spark

## Overview
This repository contains a Jupyter Notebook that demonstrates an ETL (Extract, Transform, Load) process using Apache Spark to manage COVID-19 data. The notebook reads data from CSV files, processes the data using PySpark, and loads the processed data into a MySQL database.

## Project Structure
```
Covid-19-ETL-CSV-to-MySQL-using-Spark.ipynb  - The main notebook with ETL processes.
data/                                        - Directory for storing CSV data files.
```

## Features
- **Data Extraction**: Load COVID-19 data from CSV files.
- **Data Transformation**: Perform necessary data cleaning and transformations using PySpark.
- **Data Loading**: Load the transformed data into a MySQL database for further analysis.

## Prerequisites
Before running the notebook, ensure you have the following:
- Python 3.x
- PySpark
- MySQL database
- MySQL JDBC driver

## Setup
1. **Install Python Packages**:
   ```bash
   pip install pyspark pandas numpy
   ```

2. **MySQL JDBC Driver**:
   Download the JDBC driver from the MySQL official website and ensure it is accessible to the notebook.

3. **MySQL Database Configuration**:
   Set up your MySQL database with the necessary credentials and ensure it is accessible.

## Running the Notebook
Open the Jupyter Notebook in your local environment or a platform like Google Colab that supports Python and PySpark execution. Run each cell sequentially to observe the ETL process.

## Contributing
Contributions to enhance the ETL process or extend the functionality are welcome. Please fork the repository and submit a pull request with your changes.

## License
This project is available under the MIT License. See the LICENSE file for more details.
