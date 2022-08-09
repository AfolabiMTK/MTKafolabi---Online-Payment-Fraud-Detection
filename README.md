# MTKafolabi---Online-Payment-Fraud-Detection

The project is about a bank called Blossom Bank which is also known as BB PLC. It is a multinational financial services group, that offers retail and investment banking, pension management, asset management and payment services, headquartered in London.

The solution to the project is about building a Machine Learning model to predict online payment fraud.

The Dataset contains 10 columns and 1,048, 575 rows.

The ROWS contains the number of survey carried out and it has no missing value

The COLUMNS explains the information collected and this is interpreted below:
1. step: represents a unit of time where 1 step equals 1 hour 
2. type: type of online transaction
3. amount: the amount of the transaction 
4. nameOrig: customer starting the transaction
5. oldbalanceOrg: balance before the transaction
6. newbalanceOrig: balance after the transaction
7. nameDest: recipient of the transaction
8. oldbalanceDest: initial balance of recipient before the transaction
9. newbalanceDest: the new balance of recipient after the transaction
10. isFraud: fraud transaction

As the topic depicts,  there was a rise in the fraudulent activities across different platforms, so there was need to really need to check and stop all the chances available that the fraudsters can take to continue in their bad acts.

I CARRIED OUT AN EXPLORATORY DATA ANALYSIS TO DETECT:
The types of channels used 
Top 5 earners from the fraud act
Top 5 defrauded customers
The type of online transactions that include fraud
The type of transaction with the highest amount
The average time used to defraud each customer

I DISCOVERED THAT:
The Top 14 defrauded customers from the data set were the most defrauded customers with the same amount of 10,000,000.00 each while the least defrauded is Customer C938188576 with just 0.1
The time used to defraud top defrauded customers was 95.0 and 1.0 for the least customers. But the average time is 26.9
There was a strong and positive correlation with the payment channels which can be tagged to be a successful fraud.
The fraudsters too the advantage of CASH_OUT and PAYMENT channels as the most attempted channels.
Customer C1590550415 got the highest earning from the fraud out of 1,142 customers that were defrauded. With 1,142 defrauded customers out of 1,047,433 customers, I have less than 1% of fraud.
