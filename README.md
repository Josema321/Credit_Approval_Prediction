# Credit Approval Prediction

Credit scorecards are a common risk control method in the financial industry. It uses personal information and data submitted by credit card applicants to predict the probability of future defaults and credit card borrowings. 
The bank can decide whether to issue a credit card to the applicant. Accurately predicting credit risk is crucial because issuing credit cards to customers who are likely to default on their payments can be risky.

## Problem:

- Credit scorecards are a common risk control method in the financial industry. <br/>

- It uses personal information and data submitted by credit card applicants to predict the probability of future defaults and credit card borrowings. <br/>

- The bank can decide whether to issue a credit card to the applicant. Credit scores can objectively quantify the magnitude of risk. <br/>

- This is important because issuing credit cards to customers who are likely to default on their payments can be risky. <br/>


## Objective: 
The main objective of this project is to develop a classification model capable of determining the eligibility of customers for obtaining credit. 
This model will analyze the target variable, which indicates whether a customer can be granted a credit (1) or not (0).

To achieve this objective, a thorough analysis of the provided data was conducted. 
Special emphasis was placed on selecting the most influential variables for the various models evaluated, using tools such as Xgboost, LogisticRegression GradientBoostingClassifier, and RandomForestClassifier.  <br/>

Subsequently, the hyperparameters of the most promising model were optimized using RandomizedSearchCV.

## Approach
- **Data Exploration and Preprocessing:** Initial data exploration to understand the structure and distribution of data. This includes handling missing values, encoding categorical variables, and normalizing numerical features. <br/><br/>
- **Feature Selection:** Identifying the most relevant features for the model using statistical methods and domain knowledge.  <br/><br/>
- **Model Evaluation:** Evaluating various models to determine the best fit for the data. This involves comparing performance metrics such as accuracy, precision, recall, and F1-score.  <br/><br/>
- **Hyperparameter Tuning:** Using RandomizedSearchCV for hyperparameter tuning to enhance model performance without being computationally expensive.   <br/><br/>
- **Model Validation:** Validating the model using cross-validation techniques and ensuring its robustness and generalizability.   <br/><br/>

## Results:
The best model that suited the case was Xgboost, with an accuracy of 91.45%. This model demonstrated the best balance between precision and recall, making it the most reliable for predicting credit approval.

## Resources:
The data for this project was obtained from the Kaggle platform, the dataset used it's available at https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction/data






