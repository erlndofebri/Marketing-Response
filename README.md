# Marketing-Response

A food company wants to produce the highest profit for the next direct marketing campaign, scheduled for the next month.
A pilot campaign involving 2.240 customers was carried out, customers who bought the offer were properly labeled.

After doing prediction and give proper simulation, using our model and recommendation can **potentially increase up to 19.37% conversion rate** and also can increase **40.91% revenue**

## Project Background
The objective of the team is to develop a model that predicts customer behavior whether it'll reponse the marketing or not.

Moreover, other than maximizing the profit of the campaign, the CMO is interested in understanding to study the characteristic features of those customers who are willing to buy the gadget. 

The steps are: 
1. Data Exploration 
2. Segmentation
3. Classification Model

Our goals is to get `20% conversion rate increment` and get `15% revenue increment` next year (2023)

## Dataset Overview

Our data consist of 2240 customer data. There are 27 independent features and 1 target feature. Our target feature explain whether our customer will response our campaign or not. Data Source: [link](https://www.kaggle.com/datasets/jackdaoud/marketing-data?taskId=2986)

## Data Preprocessing

1. Feature Extraction
2. Missing Values Handling
3. Outlier Handling
4. Feature Encoding
5. Feature Transformation
6. Feature Scaling
7. Feature Selection
8. Imbalaced Target Handling

## Modeling

We use 6 types of algorithm:

1. Logistic Regression
2. Decission Tree Classifier
3. Random Forest
4. Ada Boosting Classifier
5. Gradient Boosting Classifeir
6. XGB Classifier

then we try to do experiment to compare SMOTEENN and SMOTE-NC method on AUC Score

Result :
We got XGB Classifier SMOTEENN as the best model, because:
1. it has highest AUC
2. It didn't too overfitting

## Clustering:

1. Segment 1: low recency, low spending amount, low frequency
2. Segment 2: high recency, low spending amount, low frequency
3. Segment 3: low recency, high spending amount, high frequency

## Recommendation :
1. Using 15% MntMeatProducts Increment
2. Using 5% NumWebPurchase Increment
3. Using 15% Num Store Purchase Reduction
4. Discount Offering

Implementing recommendation above can potentially **increase 5.84% conversion rate** (response rate) and **increase 40.91 % Revenue**


