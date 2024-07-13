# AutomatedMLPipeline
This project is currently a beta version of take home assessment for Technical Assessment.

## Build an automated machine learning pipeline to predict the risk of loan applications
###Introduction
As a machine learning engineer in MoneyLion, you are responsible to architect and build machine learning pipelines. Machine learning pipelines are
important because they can free up data scientists from maintaining existing models manually. Automated pipelines are also useful for enforcing machine
learning governance as all newly created models are forced to adhere to required standards and best practices.

###Assignment
We have a LightGBM machine learning model in production that predicts the risk of loan applications. Our machine learning model has been
in production for the last 3 months and our monitoring systems have alerted us on possible feature drifts. Data scientists have been manually writing scripts
to preprocess their training data and tune the model to improve the model each month. As it seems clear that this model requires retraining and fine-tuning
monthly, we want to build an automated machine learning pipeline so that this loan model can get continuous updates and fine-tuning.
For this assignment, we want you to build this machine learning pipeline. This challenge is intentionally meant to be open-ended.
An input data file (loan.csv) has been provided to help you kickstart building this machine learning pipeline. This pipeline should be able to run
independently when the assessment is submitted and should only require the same input file to run from end to end.
