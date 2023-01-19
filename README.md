
# BANK LOAN RISK ANALYTICS EDA

## Business Understanding
The loan providing companies find it hard to give loans to the people due to their insufficient or non-existent credit history. Because of that, some consumers use it as their advantage by becoming a defaulter. Suppose you work for a consumer finance company which specialises in lending various types of loans to urban customers. You have to use EDA to analyse the patterns present in the data. This will ensure that the applicants capable of repaying the loan are not rejected.

When the company receives a loan application, the company has to decide for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.

2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

The data given below contains the information about the loan application at the time of applying for the loan. It contains two types of scenarios:

1. **The client with payment difficulties:** he/she had late payment more than X days on at least one of the first Y instalments of the loan in our sample.

2. **All other cases:** All other cases when the payment is paid on time.

When a client applies for a loan, there are four types of decisions that could be taken by the client/company:

- **Approved**: The Company has approved loan Application

- **Cancelled:** The client cancelled the application sometime during approval. Either the client changed her/his mind about the loan or in some cases due to a higher risk of the client he received worse pricing which he did not want.

- **Refused:** The company had rejected the loan (because the client does not meet their requirements etc.).

- **Unused offer:**  Loan has been cancelled by the client but on different stages of the process.

In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

## Business Objectives
This case study aims to identify patterns which indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.

To develop your understanding of the domain, you are advised to independently research a little about risk analytics - understanding the types of variables and their significance should be enough.

## Data Understanding

This dataset has 3 files as explained below: 
1. [application_data.csv](https://drive.google.com/file/d/1CgK3rKfqQpFVjuzq9YI5F3K1tNVeY9br/view?usp=sharing) contains all the information of the client at the time of application. The data is about whether a client has payment difficulties.
2. [previous_application.csv](https://drive.google.com/file/d/1YALbTs_1hA97Aax9wJw7_xwHZiJpEvGK/view?usp=sharing) contains information about the client’s previous loan data. It contains the data whether the previous application had been Approved, Cancelled, Refused or Unused offer.
3. [columns_description.csv](https://drive.google.com/file/d/1E4XWVgosf1-JLXr-qthyzVe4Q8L735II/view?usp=sharing) is data dictionary which describes the meaning of the variables.

## EDA Approach
1. Import necessary data science libraries such as Numpy, Pandas, Matplotlib and Seaborn to perform EDA on the given datasets.
2. Read and inspect current loan application dataset.
3. Handle missing values either by imputing it or removing the columns which contains missing values greater than threshold value (45% set in this case study).
4. Handle outliers for the potential continuous numerical variables.
5. Fix the data format which are not as expected.
6. Check data imbalance for the target variable.
7. Perform Univariate and Segmented Univariate analysis for defaulters and non-defaulters. 
8. Perform Bivariate and Multivariate analysis for defaulters and non-defaulters.
9. Perform the above same steps (2 to 8) for previous loan application dataset.
10. Provide analysis and business insights gained through EDA to business stakeholders.

## Code Implementation & Presentation Slides
**Refer Python jupyter notebook and presentation files present in this repository to know more about code implementation and business insights mentioned.**

## Contributors
- [Ganesh Jalakam](https://github.com/GaneshJalakam)
