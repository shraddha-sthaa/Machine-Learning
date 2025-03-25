# Quora-Question-Pair-Similarity

This repository contains the code and resources for the final project of the DSCI-6003-03 Machine Learning course at the University of New Haven. The project focuses on question similarity detection on the Quora platform.


## Project Description

The project investigates the effectiveness of feature engineering techniques in enhancing the performance of machine learning models for question similarity detection on Quora. We explore various feature engineering approaches, including basic techniques like token-based metrics and length-related attributes, and delve into advanced methods like fuzzy matching algorithms.

## Data

The project utilizes a dataset from the Quora platform containing question pairs labeled as similar or dissimilar. 

## Code Structure

The codebase is organized as follows:

* `data`: This folder would contain the Quora dataset. 
* `Final Project.ipynb`: This file contains Jupyter notebook for exploratory data analysis, feature engineering, model training, and evaluation.
* `reports`: This folder contains the final project report (refer to the `final_report.pdf` or `final_report.docx` file).

## Dependencies

This project requires specific Python libraries for data manipulation, machine learning modeling, and visualization. Here's how to install them:

```bash
pip install xgboost  # Gradient Boosting library
pip install distance  # Library for distance metrics
pip install fuzzywuzzy  # Fuzzy string matching library
```

The required libraries will also be specified within the Jupyter notebooks.

## Running the Project

To run the project, follow these steps:

1. Clone this repository.
2. Install the required dependencies using the commands provided above.
3. Open the Jupyter notebooks in a Jupyter Notebook environment and execute the code cells sequentially.
