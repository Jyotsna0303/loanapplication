# loanapplication
In this repo master branch will have a loan application(Spring Boot) for which test cases are not written. 
Consider master branch as legacy code in which there are some issues. 
I am going to follow TDD to solve the issues in the legacy code and push the code to solutionWithTdd branch.
 
This application is accessing third party webservices to get the data and calculate loan.

Loan Calculations:
Loan Repayment calculation example:
Term (in months) 24
Amount borrowed 1000
Interest rate 7%
Step 1 – calculate the applicable rate
Applicable rate = 1 + ( interest rate * number of years )
= 1 + (7% * 24 / 12) = 1.14
Step 2 – calculate the total repayable
Total repayable = amount borrowed * applicable rate
= 1000 * 1.14 = 1140
Step 3 – calculate the repayments
Repayments = Total repayable / term
= 1140 / 24 = 47.50
This figure must be rounded UP to the nearest integer = 48
