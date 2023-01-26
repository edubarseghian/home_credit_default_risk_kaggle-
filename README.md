# home_credit_default_risk_kaggle-

## Dataset 

The dataset of the [Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk/) Kaggle competition is composed of multiple files with information about loans taken. We're going to exclusively work with the main files: application_train.csv and application_test.csv.

This is a binary Classification task: we want to predict whether the person applying for a home credit will be able to repay its debt or not.

We will evaluate with the [Area Under the ROC Curve](https://developers.google.com/machine-learning/crash-course/classification/roc-and-auc?hl=es_419), our models will have to return the probabilities that a loan is not paid for each row.

To access the data, you only need to execute the code below. 

!pip install gdown

!gdown 1CAhmDRZLsIX1rYmUHOI8n2oatGQKGeHt
!gdown 1jXsI16FglcBCKID1c5Us-WD758D6mWMD
!gdown 1i96_nh9tU0YeQtbLGusjZxVp3cBctDGp


This will download three files:

- `application_train.csv`: Training dataset you must use to train and find the best hyperparameters on your model.
- `application_test.csv`: Test dataset, use it only when you are done choosing the model and the parameters.
- `HomeCredit_columns_description.csv`: This file contains descriptions for the columns in train and test datasets.
