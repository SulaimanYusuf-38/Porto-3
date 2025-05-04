# Portfolio Part 3: Analysis of Loan Approval Data (2024 S2)

## Description
This project focuses on analyzing a dataset related to loan approvals, designed for risk assessment and loan approval modeling. The dataset comprises 20,000 records of personal and financial data, enabling the development of predictive models to determine whether loan applications are likely to be approved or denied.

## Table of Contents
- [Task Background](#task-background)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Task Description](#task-description)
- [Methodology](#methodology)
- [Results and Visualizations](#results-and-visualizations)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [License](#license)

## Task Background
The dataset, named 'Loan Approval', includes diverse features such as demographic information, credit history, employment status, income levels, existing debt, and other relevant financial metrics. This comprehensive foundation allows for sophisticated data-driven analysis and decision-making.

### Dataset Features
The dataset includes the following columns:

| Column                        | Meaning                                       |
|-------------------------------|-----------------------------------------------|
| ApplicationDate               | Loan application date                         |
| Age                           | Applicant's age                              |
| AnnualIncome                  | Yearly income                                |
| CreditScore                   | Creditworthiness score                        |
| EmploymentStatus               | Job situation                                |
| EducationLevel                | Highest education attained                    |
| Experience                    | Work experience                              |
| LoanAmount                    | Requested loan size                          |
| LoanDuration                  | Loan repayment period                        |
| MaritalStatus                 | Applicant's marital state                    |
| NumberOfDependents           | Number of dependents                         |
| HomeOwnershipStatus           | Homeownership type                           |
| MonthlyDebtPayments           | Monthly debt obligations                     |
| CreditCardUtilizationRate     | Credit card usage percentage                 |
| NumberOfOpenCreditLines       | Active credit lines                          |
| NumberOfCreditInquiries       | Credit checks count                          |
| DebtToIncomeRatio             | Debt to income proportion                    |
| BankruptcyHistory              | Bankruptcy records                           |
| LoanPurpose                   | Reason for loan                              |
| PreviousLoanDefaults          | Prior loan defaults                          |
| PaymentHistory                | Past payment behavior                        |
| LengthOfCreditHistory         | Credit history duration                      |
| SavingsAccountBalance         | Savings account amount                       |
| CheckingAccountBalance        | Checking account funds                       |
| TotalAssets                   | Total owned assets                           |
| TotalLiabilities              | Total owed debts                             |
| MonthlyIncome                 | Income per month                            |
| UtilityBillsPaymentHistory    | Utility payment record                       |
| JobTenure                     | Job duration                                 |
| NetWorth                      | Total financial worth                        |
| BaseInterestRate              | Starting interest rate                       |
| InterestRate                  | Applied interest rate                        |
| MonthlyLoanPayment            | Monthly loan payment                         |
| TotalDebtToIncomeRatio        | Total debt against income                    |
| LoanApproved                  | Loan approval status                         |
| RiskScore                     | Risk assessment score                        |

## Task Description
The high-level goal of this notebook is to build and evaluate predictive models for loan approval based on available features. The following major tasks need to be completed:

1. Clean and preprocess the dataset for downstream data analysis tasks.
2. Build and evaluate logistic regression models using the dataset.
3. Build and evaluate K-Nearest Neighbors (KNN) models using the dataset.

**Note**: While the main steps of each task have been provided, it is essential to organize and comment on your notebook to ensure it is professional and readable.

## Methodology
1. **Data Cleaning**: Address any missing values, inconsistencies, or irrelevant data points in the dataset.
2. **Exploratory Data Analysis (EDA)**: Conduct an initial analysis to understand the dataset better and visualize key relationships.
3. **Model Building**: 
   - Implement logistic regression to predict loan approval status.
   - Implement KNN for classification and comparison of results.
4. **Model Evaluation**: Assess model accuracy and other relevant metrics to determine effectiveness.

## Results and Visualizations
The results section summarizes key findings from the analysis, including model performance metrics such as accuracy, precision, recall, and F1 score. Visualizations may include:
- Confusion matrices to visualize model performance.
- ROC curves to illustrate the trade-off between true positive rate and false positive rate.

## Conclusion
This project aims to provide insights into the factors influencing loan approval decisions, as well as the effectiveness of various predictive modeling techniques. Recommendations based on the analysis will be included.
