# Employee Salary Spark ML Pipeline

This project demonstrates an end-to-end big data pipeline using components of the Hadoop and Spark ecosystem. The pipeline integrates Apache NiFi for ingestion, HDFS for distributed storage, Hive for warehousing and SQL querying, Spark MLlib for machine learning, YARN for resource management, and HBase for storing machine-learning evaluation metrics.

The dataset contains employee salary information including experience, age, education level, department, and location. Data is ingested from GitHub using NiFi, stored in HDFS, structured in Hive, and then processed using PySpark. A Linear Regression model from Spark MLlib predicts monthly salary based on experience and age.

Model evaluation metrics including RMSE and R² are written to an HBase table using the HappyBase Python library. This project demonstrates how multiple big data technologies can be integrated to create a complete data engineering and machine learning workflow.
