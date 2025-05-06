Author: Seif Hossam

Project Description:
This project predicts real estate loan approvals using machine learning, based on historical loan application data from Dream Housing Company. The aim is to automate and speed up the loan approval process for properties in urban, semiurban, and rural areas.

Dataset and Variables:
The dataset includes the following features:

Loan_ID: Unique identifier (dropped during preprocessing)

Gender: Male or Female

Married: Applicant married (Y/N)

Dependents: Number of dependents

Education: Graduate or Undergraduate

Self_Employed: Self-employed (Y/N)

ApplicantIncome: Applicant’s income

CoapplicantIncome: Co-applicant’s income

LoanAmount: Loan amount in thousands

Loan_Amount_Term: Loan term in months

Credit_History: Applicant’s credit history

Property_Area: Urban, Semi-Urban, or Rural

Loan_Status: Target variable, loan approved (Y/N)

Problem Definition:
The project addresses the problem of lengthy and complex loan approval processes for real estate loans.

Objectives:
Automate the loan approval process using a machine learning model.

Predict loan approval outcomes based on historical application data.

Data Preparation Steps:
Dropped the Loan_ID column.

Removed null values from LoanAmount, Loan_Amount_Term, and Credit_History.

Corrected invalid entries in categorical columns (Gender, Married, Dependents, Self_Employed).

Normalized ApplicantIncome, CoapplicantIncome, and LoanAmount using log transformation.

Converted categorical variables (Gender, Married, Dependents, Education, Self_Employed, Credit_History, Property_Area, Loan_Status) to numeric format.

Scaled numeric features: ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term.

Split the dataset into 80% training and 20% testing sets.

Machine Learning Techniques Used:
Logistic Regression

Support Vector Machine (SVM)

Naive Bayes

Random Forest

Performance and Evaluation:
All models achieved an accuracy of approximately 88.52 percent on the test set.

Key Findings:
Credit History is the most influential feature affecting loan approval decisions.

Analysis of loan approval rates provides insight into approval challenges and important applicant factors such as income, credit score, and employment status.

The findings are consistent with similar projects in the field.

Usage:
Prepare and clean the dataset as described above.

Train the machine learning models using the training set.

Evaluate model performance on the test set.

Use the trained model to predict loan approval for new applications.

For more details, refer to the project code and exploratory data analysis.
