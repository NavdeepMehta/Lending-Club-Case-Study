# Project Name:  Lending Club Case Study

> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- ### Project Information

> The project is a data science project that uses the lending club data set to predict whether a loan will be defaulted or not.

### Project Background

> This company is the largest **online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures**. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to **‘risky’** applicants is the largest source of financial loss (called credit loss). **Credit loss** is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

### Project Statement

> Find the driving factors which lead to the defaulted loans which are major source of loss for the company.

### Data Set

> The data set is a csv file with the loan data for the Lending Club.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Main Takeaways :

1. Fewer Defaults Compared to Fully Paid Loans: The data shows that defaulted loans are fewer than those that are fully paid, indicating a relatively stable loan repayment behavior across the dataset.
2. High Loan Amounts in the 10,000 Range: The maximum loan amounts fall within the $10,000 range, with interest rates between 10% and 15%. This suggests that loans in this range might be more common and potentially riskier due to the higher interest rates associated with them.
3. Debt Consolidation and Credit Card Loans Predominate: Debt consolidation and credit card purposes dominate the loan types, indicating that a large portion of borrowers are seeking to consolidate debt or finance personal expenses, which might have different risk profiles.
4. Loan Amounts by Grade: Grades A, B, and C have the highest loan amounts, but grades B and C also show a higher number of charged-off customers. This highlights a need for caution when evaluating loans in these grades despite their larger loan amounts.
5. Loan Amounts by Sub Grade Categories: For each grade (A to G), the highest loan amounts are found in specific subcategories (A5, A4, B3, B4, B5,C1, C2, D2, D3, E1, E2, F1, F2, G1, G2). However, the charged-off rates within these grades remain relatively consistent, suggesting that the loan amount alone may not be the best predictor of default risk.
6. 36-Month Loans Have Lower Default Rates: Loans with a 36-month tenure show a significantly lower charged-off rate compared to 60-month loans, and more loans fall into the 36-month category. This suggests that shorter-term loans might be safer and more manageable for borrowers.
7. Loan Amount and Repayment Status: Larger loan amounts correlate with Fully Paid loans (around $60,000), indicating that higher loan amounts might be associated with better repayment behavior. Additionally, fully paid loans tend to have a higher percentage of repayment as the loan amount increases.
8. Income and Default Likelihood: Borrowers with an annual income around $40,000 are more likely to default, but the likelihood of default decreases significantly as income increases. This suggests that higher income is a good indicator of better repayment ability.
9. Borrowers in Rent or Mortgage: Borrowers living in rented properties or with mortgages are more common. However, the default rate is higher among those with mortgages, highlighting a potential risk factor for loans associated with home ownership.
10. DTI Ratio and Default Likelihood: Borrowers with a DTI ratio between 10% and 25% are more likely to default, and as the DTI ratio increases, the likelihood of default also increases. This suggests that high debt burdens relative to income could be a strong indicator of default risk.
11. Employment Length and Default Rate: Borrowers with more than 10 years of employment tend to have higher loan amounts and higher charged-off rates, indicating that longer employment doesn't necessarily guarantee better repayment behavior. Conversely, shorter employment lengths are associated with lower charged-off rates.
12. Bankruptcy Records and Default Insights: Public record bankruptcy data shows 0.0 charged-off rates, suggesting that bankruptcy may not be a significant predictor of default in this dataset, or it may be underrepresented.
13. Trends Over Time: Borrower numbers increase over the years, with a notable rise in 2011, and December and Novemberseeing the highest number of borrowers. This suggests seasonal and yearly fluctuations in loan issuance.
- Risk Factors :
1. Caution with Grade B and C Loans: Grade B and C loans, despite having higher loan amounts, have a higher percentage of charged-off loans. This suggests that loan amount alone may not be a good indicator of loan quality in these grades, and additional factors (like credit history) should be considered.
2. Low Default Rate in Short-Term Loans: 36-month loans have a significantly lower charged-off rate compared to 60-month loans, indicating that short-term loans might be less risky. However, be cautious about over-relying on loan tenure as a risk factor without accounting for other variables.
3. Income and Loan Repayment: Borrowers with an annual income around $40,000 are more likely to default, suggesting that those with moderate incomes might struggle to meet higher loan payments. Income growth should be carefully considered in future loan assessments.
4. Mortgage Borrowers Are at Higher Risk: While renters and mortgage holders are more common, those with mortgages tend to have a higher charged-off rate, which could suggest that mortgage-backed loans have greater default risk compared to other loan types.
5. Public Record Bankruptcy Data: The 0.0 rate for public bankruptcy records could indicate either a lack of bankruptcy data or that bankruptcy records do not significantly affect loan defaults. Careful interpretation of this variable is needed, as it might not offer much predictive value in this analysis.
6. Borrower Numbers Show Seasonal and Yearly Trends: While borrower numbers have increased over time, seasonal patterns (e.g., higher numbers in December and November) should be accounted for when analyzing loan issuance trends to avoid misinterpretation.

- Final Thoughts:
These insights highlight key trends in the dataset, such as loan amount, income, loan tenure, and employment length as important factors influencing loan repayment behavior. However, some of the patterns suggest that loan defaults are driven by a combination of factors, including DTI ratios, income levels, and loan purposes. Hence, it's important to approach the analysis with an understanding that these relationships may be complex, and further exploration of additional features (such as credit scores, loan-to-income ratios, or payment history) could provide deeper insights
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas version: 2.2.2
- Numpy version: 1.26.4
- Seaborn version: 0.13.2
- Matplotlib version: 3.8.0
- Plotly version: 5.24.1
- Python version: 3.10.12

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.

## Contact
Created by [@umraosr] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
