# Working_Capital_Optimization
## Aim
The strategic management of a company's current assets and liabilities is known as working capital optimization, and its goal is to improve both operational and financial health. The primary objective is to achieve optimal liquidity by balancing accounts payable (AP) and accounts receivable (AR) in a way that minimizes expenses and hazards.

The goal of this project is to use predictive modeling to forecast when suppliers and customers will make payments. The project assists in predicting the weeks when clients are expected to pay the business and when the business should pay its suppliers by examining past data. With the use of these forecasts, proactive cash flow management is made possible, guaranteeing that payments are made on time.

## Data Description
### Customer Data:
Customer ID: Unique customer identifier.
Customer Name: Customer's name.
Customer Payment Terms: Payment terms and conditions for customers.
Address: Physical address or location of the customer.
Credit Limit: Maximum credit amount extended to the customer.

### Receivables Data:
Business Code: Code representing the type of business transaction.
Customer Number: Unique customer identifier.
Customer Name: Customer's name.
Payment Date: Date of payment received.
Business Year: Year of the business transaction.
Posting Date: Date of posting the transaction.
Due Date: Date by which the payment is due.
Payterm: Payment terms for the invoice.
Invoice Currency: Currency in which the invoice is issued.
Total Open Amount: Total amount of the invoice.
USD Currency: Currency conversion rate to USD.
Total Open Amount (USD): Total amount in USD.
Invoice ID: Unique identifier for each invoice.
Is Open: Indicates whether the invoice is open or closed.
DUNNLEVEL: Dunn level of the invoice, representing the past-due status.
Credit Limit: Credit limit assigned to the customer.
Baseline Date: Baseline date for the transaction.
Region: Geographic region associated with the transaction.

### Suppliers Data:
Supplier ID: Unique supplier identifier.
Supplier Name: Supplier's name.
Payment Terms: Terms and conditions for supplier payments.
Vendor Type: Type or category of the vendor/supplier.
Supplier Category: Categorization of the supplier.

### Payables Data:
Invoice Number: Unique identifier for each invoice.
Posting Date: Date of posting the invoice.
Invoice Date: Date of the invoice.
Payment Date: Date of payment made.
Net Due Date (System Calculated Date): Calculated date for net payment due.
Supplier ID: Unique supplier identifier.
Invoice Amount: Total amount of the invoice.
Fiscal Year: Financial year associated with the invoice.
Overdue: Indicates if the payment is overdue.
Invoice Status: Status of the invoice (e.g., paid, outstanding).
Spend Category: Categorization of the expenditure.
Total Outstanding Amount: Total amount outstanding for the invoice.
Late Payment Fees: Fees charged for late payments.
Payterm_n: Payment terms for the invoice.
Vendor Type: Type or category of the vendor/supplier.

## Procedure

Performed Exploratory Data Analysis(EDA) and feature engineering on both the Accounts Payable(AP) and Accounts Receivable(AR) and then maade predictive models such as RandomForestRegressor, LinearRegression, KNeighborsRegressor, GradientBoostingRegressor, and SVR to predict the week of customer payment.
Finally, grouped and summed the amount to receive and amount to pay by week and calculated the working capital by taking difference of both for every week.
