Lending Club Case Study
Goals of data analysis:
Lending loans to ‘risky’ applicants is the largest source of financial loss
(called credit loss). The credit loss is the amount of money lost by the lender 
when the borrower refuses to pay or runs away with the money owed.  

The main objective is to be able to identify these risky loan applicants, 
then such loans can be reduced thereby cutting down the amount of credit loss. 
Identification of such applicants using EDA is the aim of this case study.   

Perform an analysis to understand the driving factors (or driver variables)
behind loan default, i.e.the variables which are strong indicators of default.  
The company can utilise this knowledge for its portfolio and risk assessment. 


Please find the csv file and excel file which contains the explanation of various columns on data 
directory.
Please run the jupyter notebook script by script to avoid errors.


Step 1: Data Cleaning 1

Step 2: Univariate Analysis

Insights from above univariate plots:
There is a more probability of defaulting when :
* From above plots we can see that average default rate across all categories is 14.4% and non-default rate is 85.4%.
* People with experience 1 and 10 years are purchasing more loans.
* B type grade take the lead(30.3%), followed by the A type grades(26%).
* The highest probality to default is debt_consolidation.


Step 3: Segemented Univariate Analysis

Insights from Univariate segmented Analysis on derived variiables:
There is a more probability of defaulting when :
* From the above graphs we can see that people with less experience have high chance of default.
* People lying in medium dti range have high chances of default.
* People who have high loan to annual income ratio are at high risk of defaulting.
* Grades B,Cand D are at high probablity of defaulting.


Step 4: Bivariate/Multivariate Analysis

Observations From Bivariate Analysis:
* The above analysis with respect to the charged off loans.There is a more probability of defaulting when :
* Applicants who have taken a loan in the range 30k - 35k and are charged interest rate of 15-17.5 %.
* Applicants who have taken a loan for small business and the loan amount is greater than 14k.
* Applicants whose home ownership is 'MORTGAGE and have loan of 14-16k.
* Maximum number of defaults occured when the loan was sanctioned/issued in month December.
* Loan issued in the year 2011 also defaulted more as compared to other years.
* When grade is F and loan amount is between 15k-20k.
* When employment length is 10yrs and loan amount is 12k-14k.
* For grade G and interest rate above 20%.
* This can be a pretty strong driving factor for loan defaulting.
* The interest rate for charged off loans is pretty high than that of fully paid loans in all the loan_amount groups.
* Applicants who have taken a loan in the range 30k - 35k and are charged interest rate of 15-17.5 %.
* Applicants taking loan for 'home improvement' and have income of 60k -70k.
* Applicants whose home ownership is 'MORTGAGE and have income of 60-80k.
* Across all the income groups, the loan_amount is higher for people who defaulted.
* Applicants who receive interest at the rate of 21-24% and have an income of 60k-70k.


Step 5: Results

Contributor
Athul Das

Developed as part of the Exploratory Data Analysis Module required for Post Graduate Diploma in Machine Learning and AI - IIIT,Bangalore.