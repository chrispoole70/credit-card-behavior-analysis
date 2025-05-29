# credit-card-behavior-analysis

## Project Overview
This project is an example of how to predict clusters for credit card holders. It uses a dataset from Kaggle called [Credit Card Dataset for Clustering](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata/data).

## Instructions

The Jupyter notebook [credit-card-behavior-analysis.ipynb](https://github.com/chrispoole70/credit-card-behavior-analysis/blob/main/credit-card-behavior-analysis.ipynb) contains the code and runs using AWS SageMaker. In your AWS account you will need:
* An S3 bucket called `credit-card-behavior-analysis` that contains the file from Kaggle called `CC GENERAL.csv`
* An IAM role with the appropriate permissions including access to this bucket to use SageMaker
