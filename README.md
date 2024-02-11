## Objectives of the study
-Build a machine learning model that predicts customer churn

-Idenfiy factors that highly contribute to churn

-Provide inferential statistics and visualisations based on this data.

## Project Overview
SyriaTel Communications is a Telecommunications company that is looking to predict and prevent customer churn. Customer churn is when a customer discontinues  services with SyriaTel.This is a major problem for many service providing companies since it is very expensive since they have to incur customer acquisition cost to replace the costomer.To help SyriaTel with the cutomer churn problem , we will build a machine learning classifier model that will predict customer churn. This will help SyriaTel have a robust strategy on how to prevent customers from churning. 

## Data 
This project uses a  Churn in Telecom dataset from Kaggle.
The target variable is in the churn column.
The dataset encompasses various features, including both locational details (state and area_code) and plan specifics such as call minutes, charges, and customer service calls. Additionally, it indicates whether customers have international plans and/or voice mail plans. Through multiple model iterations, we analyzed subsets of these features along with aggregated versions to discern which ones most accurately predict customer churn.
The data can be downloaded directly from kaggle  or from this repo in Data.csv file.

## Models used
For this project, the models we used are
- Decisioin Tree Classifier
- Logistic Regression Classifier
- Random Forest Classifer
- XGBoost Classifier
- KNN Classifier
- Support Vector Machine

We used recall score to score our models and assesed the best performing model using the test data.
We opted for recall since we wish to reduce the cost incurred by a lot of false negatives.It woulde be more costly for the company if the model predicted that a customer would stay with SyriaTel when in fact that would churn/leave. This would lead to a missed opportunity for the company to dedicate retention resources towards that customer and keeping their business.

