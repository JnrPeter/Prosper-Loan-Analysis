# Prosper-Loan-Analysis

## Description of Project Files 

- Prosper_Loan_Exploration Analysis : Contains the Exploratory analysis of the dataset , visualizations and the code used to perform the analysis.
- Prosper_Loan_Explantory : Contains the Explantory analysis of the specific insights choosen from the exploratory analysis with polished visualizations.
- Prosper_Loan_Slide_Deck.slides : A slide deck presentation of specific insights from the explanatory analysis.
- README.md : A file containing an overview, summary and description of the entire Project.

## Dataset

> The dataset used for this Project was a Prosper Loan Dataset provided by Udacity.The dataset contains loan information of approximately 113,937 loans, with 81 variables/features (categorical and numerical) which reference either loan information or borrower information.


## Summary of Findings

> The analysis of the dataset first began with a Univariate Exploration of the variables in the dataset. The distribution of the Original Loan Amounts was found to have very large range of values and was heavily right skewed.It was also discovered that 53% of borrowers are Homeowners, whilst 47% of borrowers aren't. Investigation into the distribution of the borrower states revealed California to be the state with the highest number of borrowers.Whilst about 65,944 borrowers were employed at the time they posted the listing,the most common reason stated by borrowers for taking a loan was for Debt Consolidation.Most borrowers also prefer to take out a 38 month loan term.  

> To explore the relationships between pairs of variables, a bivarate exploration was performed.It was discovered that as the interest rate increases the lender's yield increases. This is an intuitive insight because the yield is how much the lender makes on a loan, so as the interest rate increases the lender's yield is bound to increase. The Prosper risk score which ranges from 1-10, with 10 being the best, or lowest risk score showed a negative correlation with borrower interest rate.With the average borrower interest rate decreasing as the prosper risk score increases.The interest rate for borrowers who specified Not Available (which corresponds to a listing category of 0) on thier listing recieved higher interest rate compared to other borrowers who specified other reasons.

>Finally, a multivaraite exploration of the variables in the dataset was performed to explore the realtionships between multiple variables.There was a postive effect on the correlation between lender's yield and borrower rate. The lender's yield for a 36 month loan term was higher than the 60 and 12 month loan terms. An upward trend in monthly income as prosper risk score increases for both homeowners and non Homeowners was discovered. Borrowers who are Homeowners earn higher monthly salaries than non-Homeowners.


## Key Insights for Presentation

> The key insights used for the presentation focuses on certain variables/features related to the borrower and how they impact the loans taken out by borrowers. The insights shared transitioned from univarate to bivarate and then multivarate, just like in the analysis of the dataset.For the individual features/variables,I focus on the distribution of Prosper risk score amongst Borrowers, the Distribution of Loan Status,Percentage of Borrowers are HomeOwners and  Distribution Stated Montly Income of Borrowers and Loan Term.  I then presented on the the relationship between the loan status of borrowers and Monthly Income and the Relationhip between Loan term and Homeowners. The final insight presented was whether stated monthly income of borrower had an effect on Prosper risk score and homeownership. Appropraite color palettes are used for each visualization in the presentation for clear communication of insights.
