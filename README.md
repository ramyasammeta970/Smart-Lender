# Smart-Lender
Smart Lender is a machine learning-powered web application designed to predict the creditworthiness of loan applicants, enabling banks and financial institutions to make faster, data-driven loan approval decisions. The platform leverages classification algorithms Decision Tree, Random Forest, K-Nearest Neighbors (KNN), and XGBoost to evaluate applicant data and determine the likelihood of loan repayment or default.

 

The application processes structured applicant inputs such as gender, marital status, education, employment status, income, loan amount, loan term, credit history, and property area. After training and evaluating all four models, the best-performing model (XGBoost at 94.7% training accuracy and 81.1% testing accuracy) is saved and integrated into a Flask web application for real-time prediction.

 

Built with Python and Flask and designed for deployment on IBM Cloud, Smart Lender provides a seamless user interface where applicants can submit their details and instantly receive an approval prediction. The system empowers financial analysts, credit officers, and banking professionals to reduce non-performing assets and improve the overall credit evaluation process with confidence.

**Scenario 1:&#x20;****Fast-Track Approval for Low-Risk Applicants**

A bank credit officer enters the details of a salaried applicant with a good credit history and stable income. The model predicts loan approval with high confidence, allowing the officer to fast-track the application without manual review.

**Scenario 2:&#x20;****High-Risk Applicant Detection**

An applicant with irregular self-employment income and no credit history submits a loan request. The system flags the application as high-risk based on the trained model, prompting further scrutiny or document verification before proceeding.

**Scenario 3:&#x20;****High-Risk Applicant Detection**

A financial analyst uses the platform to batch-evaluate multiple applicants during a high-volume period. By relying on the XGBoost model’s predictions, the analyst significantly reduces evaluation time while maintaining accuracy and compliance.
