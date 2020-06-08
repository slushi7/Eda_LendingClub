# Eda_LendingClub
Performing Exploratory Data Analysis on LendingClub Dataset 

## Objective:
To perform Exploratory Data Analysis on certain attributes of the LendingClub dataset and get insights.

The attributes that we choose are:

1.loan status
2.purpose
3.loan amount
4.interest rate
5.grade
6.sub grade
7.employee length
8.term

## About the dataset:
This dataset has be obtained from Kaggle and is provided by the LendingClub. We have used a part of the dataset.

It contains 252971 rows and 53 columns.

The target variable is loan_status (Charged off,Fully paid).

## Conclusions:
We found various insights upon performing Explorartory data analysis.

The major insights are:

1.The loan status is imbalanced, since it is the target variable we cant afford it to imbalanced.
2.Debt consolidation was the main purpose for taking a loan from the lendingclub for over 50% of the people.
3.A high number of people took loans for 10,000 dollars.
4.Close to 35% of people had interest rates between 12% to 14%.
5.Interest rate depends on the persons grade and sub grade.
6.Charged off people had higher interest rates compared to Fully Paid people.
7.Employee duration doesnt affect the interest rate or loan amount.
8.Customers with more 10 years of employee length seek loans the most.

If the LendingClub wants to reduce the number of charged off customers then they have to do the following:

1. Reduce the interest rates.
2. Reduce the amount of loans given to customers with 10+ years of experience.

This advice is based on basic EDA performed.
