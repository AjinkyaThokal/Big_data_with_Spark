# Big_data_with_Spark

# Project Overview
Welcome to the Data Processing Pipeline repository! This project showcases a comprehensive data processing workflow that involves extracting data from MySQL, transforming it using PySpark and Hive, storing the processed data in Parquet and ORC file formats.

# Description
This repository demonstrates a step-by-step data processing pipeline that enables you to efficiently handle and analyze large volumes of data using popular big data tools and technologies. The pipeline involves the following stages:

**Data Extraction:**
We start by connecting to a MySQL database using the MySQL Connector. This connector helps us extract the necessary data from MySQL and prepares it for further processing.

**Data Transformation with PySpark and Hive:**
The extracted data is processed and transformed using PySpark, a powerful Python library for big data processing. Additionally, we leverage the capabilities of Apache Hive, a data warehousing and SQL-like query language, to further refine and structure the data and we filled "NULL" Values.

**Data Storage in Parquet and ORC Formats:**
Processed data is stored in both Parquet and ORC file formats. These columnar storage formats optimize data storage and retrieval, resulting in improved performance and reduced storage requirements.


# Key Features
**End-to-End Pipeline:** This repository provides a complete data processing pipeline from data extraction to loading into HBase.
**Utilization of PySpark and Hive:** Take advantage of PySpark's data processing capabilities and Hive's SQL-like querying for enhanced data manipulation.
**Optimized Storage:** Store data in Parquet and ORC formats to optimize storage space and query performance.

# Repository Structure

**Python_mysql:** In this we have written Python code to take data from MySQL Database.
**spark_driver_program:** This is the final script which contains Pyspark Code.
