## Project information
***Category:*** Classification problem     
***Goal:*** Predict if a loan application will be accepted by the bank

## What is this project about ?
This project is taken from a competition on Vidhya Analytics. 
The objective is to predict whether a loan application will be accepted in order to automate the loan egibility process for the banks,considering lots of datas like age, income, gender, loan amount, credit history and many others. 

## Intro
In finance, a loan is the lending of money by one or more individuals, organizations, or other entities to other individuals, organizations etc. The recipient (i.e., the borrower) incurs a debt and is usually liable to pay interest on that debt until it is repaid as well as to repay the principal amount borrowed.
  
This notebook is to predict which of the customers will have their loan approved.  
Our aim from the project is to make use of pandas, matplotlib, & seaborn libraries from python to extract insights from the data and  xgboost, & scikit-learn libraries for machine learning.
   
And in the end, to predict whether the loan applicant can replay the loan or not using voting ensembling techniques of combining the predictions from multiple machine learning algorithms.

## Major observation from the data

1. Applicants who are male and married tends to have more applicant income whereas applicant who are female and married have least applicant income

2. Applicants who are male and are graduated have more applicant income over the applicants who have not graduated.

3. Again the applicants who are married and graduated have the more applicant income.

4. Applicants who are not self employed have more applicant income than the applicants who are self employed.

5. Applicants who have more dependents have least applicant income whereas applicants which have no dependents have maximum applicant income.

6. Applicants who have property in urban and have credit history have maximum applicant income

7. Applicants who are graduate and have credit history have more applicant income.

8. Loan Amount is linearly dependent on Applicant income

9. From heatmaps, applicant income and loan amount are highly positively correlated.

10. Male applicants are more than female applicants.

11. No of applicants who are married are more than no of applicants who are not married.

12. Applicants with no dependents are maximum.

13. Applicants with graduation are more than applicants whith no graduation.

14. Property area is to be find more in semi urban areas and minimum in rural areas.


