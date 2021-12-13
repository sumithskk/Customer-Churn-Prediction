# Customer-Churn-Prediction
## What is Customer Churn ?
![churn](https://user-images.githubusercontent.com/42634704/144177098-0fc20a64-4e28-42c7-8fc5-895c27eaf9f5.png)
Customer churn (or customer attrition) is a tendency of customers to abandon a brand and stop being a paying client of a particular business. 

The percentage of customers that discontinue using a company’s products or services during a particular time period is called a customer churn (attrition) rate.
## Churn Workflow
![customerchurn_workflow](https://user-images.githubusercontent.com/42634704/144177148-bed9ddd7-d12c-44de-bf0e-bb896ed2a3f3.png)



## Dataset
Telecom Dataset - The sample data tracks a telecommunications company. It includes a target label indicating whether or not the customer, and other dependent features that cover demographics, services that each customer has signed up for, and customer account information. It has data for 7043 clients, with 20 features.

![churn_percentage](https://user-images.githubusercontent.com/42634704/144177383-eda08cee-79b5-4054-bc49-5259eea88880.png)

## Modelling
* EDA - Split the attributes into multiple categories : DEMOGRAPHIC FEATURES,SERVICE FEATURES,PAYMENT FEATURES
* Used pycaret classification for modelling (Easy to use: Compared with sklearn models)
* Used metrics - F1 Score

## Setup -Pycaret
* Install Pycaret Package on Anaconda environment

          #create a conda environment
          conda create --name yourenvname python=3.6
          #activate environment
          conda activate yourenvname
          #install pycaret
          pip install pycaret
