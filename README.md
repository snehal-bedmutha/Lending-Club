# Lending-Club
https://www.kaggle.com/ionaskel/credit-risk-modelling-eda-classification/data

Our dataset has 887,380 rows and 77 different features. The predictor column loan_status had a lot of values present in it and we converted it into a binary parameter of Good loan and Bad loan.
Bad Loan: If the loan status is any of the following:
<li>
•	'Charged Off'
•	'Default'  
•	"Does not meet the credit policy.
•	"In Grace Period“
•	"Default Receiver“
•	"Late (16-30 days)“
•	"Late (31-120 days)")
</li>

Good Loan: If the loan status is ‘Fully Paid’
We normalised different parameters and created binary features. We had to do thorough analysis to understand different jargons of the loan industry. We also did exploratory analysis of the data and tried various permutations and combinations of parameters to find the best features which helped provide distinction between the loans. 
Selected Features:

<li>
•	loan_amnt – Amount of loan taken by the customer.
•	total_pymnt – Total payment made till that date.
•	total_rec_late_fee – Total amount of late fee charged for delayed payments.
•	int_rate – The interest rate on the loan.
•	Grade – Grade of the loan taken as provided by the bank.
•	emp_length – Number of years the customer is employed.
•	home_ownership – Does the customer own a home?
•	annual_inc – The annual income of the customer
•	Term – The total length of the loan
•	Region – State where the loan is taken
•	Loan title- type of loan disbursed
</li>
