Link to Deployed Model: https://app-app-88b5rvk45nznh6jcz7ss6g.streamlit.app/ 


Credit Default Prediction Model

This project demonstrates the end-to-end CRISP-DM (Cross-Industry Standard Process for Data Mining) workflow through the deployment of a machine learning model. It was developed as part of CIS 412: Machine Learning in Business Applications, where I served as a Teaching Assistant (TA).

This is the first deployed machine learning model in the history of the course, designed to give students practical exposure to the entire pipeline—from business understanding and data preparation to modeling, evaluation, and deployment.

🚀 Project Overview

The model predicts whether a customer will default on a loan based on financial, demographic, and categorical attributes.

The app allows users to input customer details and view:

Prediction (Default / No Default)

Probability of Default

Probability of No Default

📊 Input Features
Numerical Features

Months Loan Duration

Loan Amount

Percent of Income

Years at Residence

Age

Categorical Features

Checking Balance (A11)

Credit History (A34)

Purpose (A43)

Savings Balance (A65)

Employment Duration (A75)

Other Credit (A143)

Housing (A152)

Job (A173)

Phone (A192)

📈 Example Prediction

Input:

Months Loan Duration: 24

Loan Amount: 4000

Percent of Income: 30

Years at Residence: 2

Age: 32

Credit History: A34

Purpose: A43

Output:

Prediction: Default

Probability of Default: 0.81

Probability of No Default: 0.19

🛠️ CRISP-DM Phases Demonstrated

Business Understanding – Business risk: predicting loan defaults.

Data Understanding – Exploring financial and demographic loan data.

Data Preparation – Encoding categorical features, scaling numerical features, handling missing values.

Modeling – Training supervised classification models (e.g., logistic regression, tree-based models).

Evaluation – Using metrics such as accuracy, AUC, precision/recall.

Deployment – Interactive app where students can test predictions with real-time inputs.

💡 Educational Impact

Shows students how theory connects to practice.

Makes CRISP-DM tangible by walking through every stage.
