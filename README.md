# Project Loan Approval Prediction 🏦 💰

## The Team: Joel, Johana, Lucie, Manuel  👓


## Project Overview 📑
We are developing a machine learning model to predict whether a loan will be approved or rejected based on various features of the applicants. 
This prediction helps the bank make informed lending decisions.
 
### Data Cleaning: 
- Removed leading and trailing spaces from both column names and data entries to ensure clean data for processing.
- Dropped the `loan_id` column as it is non-relevant for modeling.
- Removed leading and trailing spaces from both column names and data entries.

### Feature Engineering: 
- Created a new column named **`Total_Asset_Value`**, which is the sum of the following asset columns:
  - `residential_assets_value`
  - `commercial_assets_value`
  - `luxury_assets_value`


### Encoding: 
Categorical variables: (like education and self_employed) were converted into dummy variables using one-hot encoding, allowing effective handling of these features in machine learning models.
Normalization/Standardization: The dataset was normalized and standardized to see which method yielded better accuracy.

## Normalization and Standardization 🔧
 The dataset was normalized using **Min-Max Scaling** and standardized using **Standard Scaler** to observe which method yields better accuracy for the predictive models.

## Machine Learning 🧠
### Techniques used 🧰
1. **Logistic Regression**
2. **K-Nearest Neighbors (KNN)**
3. **Decision Tree** 

## Model performances and Key findings 🗝️
- **Logistic Regression**:
  - Normalized Model:
    - Accuracy: 91.22%
    - Precision: 89%
    - Recall: 87%
    - F1 Score: 88%
    - AUC-ROC: 97%

- **Decision Tree**:
  - Accuracy rate: 97%
  - Precision: 98%

- **KNN**:
  - Normalized Model:
    - Accuracy: 90%
    - Precision: 86%
    - Recall: 88%
    - F1 Score: 87%
  
## Result 📈
The evaluation of the models highlighted Decision Tree as the most effective model for predicting loan approvals. 
Logistic Regression and KNN also provided strong performance but were outperformed by the Decision Tree.
Credit Score is the most influential feature, indicating its critical role in determining loan approvals.

## Conclusion : ✔️
The project demonstrated how machine learning can enhance decision-making in the banking sector. 
By analyzing various features and their impact, we were able to build robust predictive models. 
Future work could include exploring advanced algorithms, incorporating additional features, and improving model interpretability.

## Datast Source:
https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset 
