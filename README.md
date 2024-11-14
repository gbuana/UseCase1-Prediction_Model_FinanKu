# UseCase1-Prediction_Model_FinanKu
Case Study 1_Model Prediksi Pelanggan Gagal Bayar Kartu Kredit

**PROBLEM STATEMENT**

Concern about delays in credit card payments on FinanKu which will harm business. So that people who have the potential to experience late payments can be predicted more quickly to determine appropriate strategies for dealing with future conditions.

**OBJECTIVE**

Create a model that can predict at least 60% of customers who will experience late credit card payments [Accuracy & Recall above 60%]

**AVAILABLE VARIABLES**

From the dataset we have, there are several data available:

1. Customer ID: Unique ID Customer
2. Branch: Registered Customer Branch Location
3. City: Location of Registered Customer's City
4. Age: Customer Age During the Observation Period
5. Avg. Annual Income/Month: Average customer income in one year
6. Balance (Q1-Q4): Saldo mengendap yang dimiliki nasabah di akhir kuartal
7. Num of Products (Q1-Q4): The customer's settled balance at the end of the quarter
8. HasCrCard (Q1-Q4): Customer credit card product ownership status at the end of the quarter
9. Active Member (Q1-Q4): Customer active status
10. Unpaid Tagging: Customer status in default

**EXPERIMENT**

Review Period:

- Customers are reviewed for the past year
- Customers are reviewed for the last 6 months

Variable Adjustment:

- Balance is seen as an average over a time horizon & changes are seen at the end of the review and the beginning of the review
- View the average, maximum, and minimum product count holdings in the review period
- Customer activity status is seen in the form of months
