# Credit_Appraisal_NBFC
Train data claenning and Handling missing values
Outlier Identfiaction and Outlier Removal
Balancing Imbalanace Data set by ovr sampling
Train Data set to  splited in to train and  test 
Test Data set to for understanging Data modelling
Base Model creation
Feature Selections methods vif ,Extra tree clasifier
new Model creation multiple model  creation with secected features .
Model Performace evaluation based on Accuracy, precision, Recall, f Score and Area under curve
Optimazation  & Model Hyperparameter tunning
selecting  Best Model based on peformace and considered parameter as per Business case and problem statement
Justifiaction of model selection overall evaluation 
Note that Test data is the data which needs to be predicted using clean test data
Test Data set have Load Id of respective client along with other details.
Cleaning of test data along with missing values .
Load Eligibilty prediction for the given data set names as test data set.

Credit Appraisal for NBFC

Overview

This project focuses on developing a robust machine learning solution for a Non-Banking Financial Company (NBFC) to evaluate customer eligibility for loans. The primary objective is to identify customers who are eligible for loans while minimizing false positives, which could lead to bad debts, and false negatives, which could result in lost potential customers.

Key Highlights

Data Preprocessing

Data Cleaning:

Handling missing values effectively.

Removing unnecessary or duplicate records.

Outlier Detection and Removal:

Identifying extreme values that could skew the model performance.

Applying appropriate techniques to mitigate their impact.

Balancing the Dataset:

Addressing class imbalance issues to ensure the model is not biased towards majority classes.

Model Development

Splitting Data:

Dividing the dataset into training and testing subsets for model training and evaluation.

Base Model Creation:

Establishing a baseline model to benchmark improvements.

Feature Selection:

Identifying the most significant features for predicting loan eligibility.

Model Evaluation Metrics:

Accuracy

Precision

Recall

F1-Score

Area Under the Curve (AUC)

Optimization and Tuning

Hyperparameter Tuning:

Optimizing model parameters to enhance performance.

Model Selection:

Comparing models based on evaluation metrics and business requirements.

Emphasizing models with lower false positives to mitigate bad debt risk.

Justification of Model Selection:

Providing detailed reasoning behind the chosen model based on performance metrics and alignment with the business problem.

Business Problem Context

The business challenge involves predicting the eligibility of customers for loans based on a binary classification problem. Each test data entry includes a unique loan ID, customer details, and other relevant attributes. The desired outcome is to:

Identify true positives (eligible customers who repay loans).

Minimize false positives (ineligible customers mistakenly classified as eligible, leading to bad debts).

Account for false negatives (eligible customers wrongly denied loans, resulting in lost opportunities).

Classification Cases

Case 1: Loan taken and repaid (True Positive).

Case 2: Loan taken but not repaid (False Positive).

Case 3: Eligible but not given loan (False Negative).

Case 4: Not eligible and no loan granted (True Negative).

Business Impact

High false positives are detrimental as they result in financial losses due to bad debts.

False negatives, while less critical than false positives, lead to missed opportunities and reduced customer satisfaction.

The balance between these metrics is critical to optimize profitability and minimize risk for the NBFC.

Results

Multiple classification models were developed and evaluated.

The final model was selected based on its ability to minimize false positives while maintaining a reasonable false negative rate.

The selected model achieved an optimal trade-off between accuracy and business-driven performance metrics.

Conclusion

This project demonstrates the development of a data-driven solution tailored for NBFCs to evaluate loan eligibility. By incorporating business requirements into the model evaluation process, the solution ensures better risk management and profitability.

For further details, feel free to explore the project files and notebooks included in this repository. Contributions and feedback are welcome!
