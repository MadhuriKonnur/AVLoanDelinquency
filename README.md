## Loan Delinquency Prediction

Given the information like mortgage details, borrowers related details and payment details, our objective is to identify the delinquency status of loans for the next month given the delinquency status for the previous 12 months (in number of months)

**Dataset Used:** Provided by Analytics Vidhya.

[https://datahack.analyticsvidhya.com/contest/india-ml-hiring-hackathon-2019/](https://datahack.analyticsvidhya.com/contest/india-ml-hiring-hackathon-2019/)

Contains both train.csv and test .csv along with sample submission .csv file

### **Data Dictionary**

| **Variable** | **Description** |
| --- | --- |
| loan\_id | Unique loan ID |
| source | Loan origination channel |
| financial\_institution | Name of the bank |
| interest\_rate | Loan interest rate |
| unpaid\_principal\_bal | Loan unpaid principal balance |
| loan\_term | Loan term (in days) |
| origination\_date | Loan origination date (YYYY-MM-DD) |
| first\_payment\_date | First instalment payment date |
| loan\_to\_value | Loan to value ratio |
| number\_of\_borrowers | Number of borrowers |
| debt\_to\_income\_ratio | Debt-to-income ratio |
| borrower\_credit\_score | Borrower credit score |
| loan\_purpose | Loan purpose |
| insurance\_percent | Loan Amount percent covered by insurance |
| co-borrower\_credit\_score | Co-borrower credit score |
| insurance\_type | 0 - Premium paid by borrower, 1 - Premium paid by Lender |
| m1 to m12 | Month-wise loan performance (deliquency in months) |
| m13 | target, loan deliquency status (0 = non deliquent, 1 = deliquent) |

For coding I have used **Google Colab python 3 Notebook**.

For more details, please refer to my GitHub repo link [https://github.com/MadhuriKonnur/AVLoanDelinquency](https://github.com/MadhuriKonnur/AVLoanDelinquency)