# network-attack-detection-pyspark
Distributed ML project for DoS and PortScan detection using PySpark and CICIDS2017

# Network Attack Detection with PySpark

Distributed machine learning project for detecting malicious network activity, with a focus on DoS and PortScan attacks using the CICIDS2017 dataset.

## Overview
This project explores how to detect network attacks using big-data tools and machine learning. The workflow uses PySpark, Hadoop/HDFS, and MLlib to process network traffic data and build predictive models.

## Objectives
- Detect malicious traffic related to DoS and PortScan activity
- Process large-scale network data in a distributed environment
- Compare machine learning models for classification performance

## Tech Stack
- Python
- PySpark
- Hadoop / HDFS
- MLlib
- Jupyter Notebook

## Dataset
- CICIDS2017

## Approach
- Loaded and merged multiple traffic files into a single dataset
- Cleaned and prepared data for analysis
- Selected relevant network traffic features
- Built and compared Logistic Regression and Random Forest models

## Results
Random Forest achieved very strong performance, with ROC AUC close to 0.99 for both DoS and PortScan detection.

## Files
- `network_attack_detection_pyspark.html`: exported notebook/code
- `project_summary.pdf`: project write-up

## Future Improvements
- Add a cleaned notebook version
- Improve feature engineering
- Extend the approach to additional attack categories
