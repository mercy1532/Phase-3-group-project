![image](https://github.com/ellahad/Phase-3-Project-/assets/145706145/bac914cc-725f-4d02-be80-679a97e184f7)
# Analysis for Predicting and preventing customer churn for SyriaTel company

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

We used recall score to score our models and assesed the best performing model using the test data.
We opted for recall since we wish to reduce the cost incurred by a lot of false negatives.It woulde be more costly for the company if the model predicted that a customer would stay with SyriaTel when in fact that would churn/leave. This would lead to a missed opportunity for the company to dedicate retention resources towards that customer and keeping their business.

## Model Evaluation
From our analysis, after tuning the models the best performing model was XGBoost with
Training Accuracy: 0.9995621716287215
Train Recall: 0.999124343257443
Train Precision: 1.0
Train F1 Score: 0.9995619798510731
Test Accuracy: 0.9985007496251874
Test Recall: 0.9900990099009901
Test Precision: 1.0
Test F1 Score: 0.9950248756218906
The recall for both train data and test data were so close to mean our model was performing well.
## Conclusions
### Feature importance
From the feature importance plot total charges, voice mail plan and international plan were the top three features that highly impact churn. And for state Michigan alse came out as an important feature.
![image](https://github.com/ellahad/Phase-3-Project-/assets/145706145/c58334b6-e278-46d6-ac84-29b975807c0c)

### Recommendations
Enhance Service Quality: Focus on improving the quality of service for features like total charges, voice mail plans, and international plans. Ensuring these services meet or exceed customer expectations can help retain existing customers and attract new ones.

Personalized Offerings: Utilize the insights gained from the analysis to tailor personalized offerings or promotions targeting customers who are at risk of churning. Offering incentives or discounts on international plans or voice mail services could encourage customers to stay with SyriaTel.

Customer Engagement: Implement strategies to increase customer engagement and satisfaction. This could include regular communication through personalized messages or emails, seeking feedback to address concerns promptly, and providing timely customer support.



