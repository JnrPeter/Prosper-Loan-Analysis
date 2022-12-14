# Prosper-Loan-Analysis

## Description of Project Files 

- Prosper_Loan_Exploration Analysis : Contains the Exploratory analysis of the dataset , visualizations and the code used to perform the analysis.
- Prosper_Loan_Explantory : Contains the Explantory analysis of the specific insights choosen from the exploratory analysis with polished visualizations.
- Prosper_Loan_Explanatory.slides : A slide deck presentation of specific insights from the explanatory analysis.
- README.md : A file containing an overview, summary and description of the entire Project.

## Overview of the Project

> The Project has been divided into two phases, Part 1 and Part 2. The Part 1 focuses on the exploratory analysis of the dataset, whilst part two focuses on the explanatory analysis of the insights gained from part one. The dataset used for this Project was a Prosper Loan Dataset provided by Udacity.The dataset contains loan information of approximately 113,937 loans, with 81 variables/features (categorical and numerical) which reference either loan information or borrower information.


## Summary of Findings

> The analysis of the dataset first began with a Univariate Exploration of the variables in the dataset. The distribution of the Original Loan Amounts was found to have very large range of values and was heavily right skewed.It was also discovered that 53% of borrowers are Homeowners, whilst 47% of borrowers aren't. Investigation into the distribution of the borrower states revealed California to be the state with the highest number of borrowers.Whilst about 65,944 borrowers were employed at the time they posted the listing,the most common reason stated by borrowers for taking a loan was for Debt Consolidation.Most borrowers also prefer to take out a 38 month loan term.  

> To explore the relationships between pairs of variables, a bivarate exploration was performed.It was discovered that as the interest rate increases the lender's yield increases. This is an intuitive insight because the yield is how much the lender makes on a loan, so as the interest rate increases the lender's yield is bound to increase. The Prosper risk score which ranges from 1-10, with 10 being the best, or lowest risk score showed a negative correlation with borrower interest rate.With the average borrower interest rate decreasing as the prosper risk score increases.The interest rate for borrowers who specified Not Available (which corresponds to a listing category of 0) on thier listing recieved higher interest rate compared to other borrowers who specified other reasons.

>Finally, a multivaraite exploration of the variables in the dataset was performed to explore the realtionships between multiple variables.There was a postive effect on the correlation between lender's yield and borrower rate. The lender's yield for a 36 month loan term was higher than the 60 and 12 month loan terms. An upward trend in monthly income as prosper risk score increases for both homeowners and non Homeowners was discovered. Borrowers who are Homeowners earn higher monthly salaries than non-Homeowners.



