Fraud Transaction Analysis (Exploratory Data Analysis)

Internship Information
This project is completed as part of the Oasis Infobyte – Data Analytics Internship.

Project Overview
The objective is to analyze financial transaction data to identify patterns of fraudulent activities. Using EDA, the project examines transaction behavior, fraud distribution, and trends over time.

Problem Statement
Fraudulent transactions pose risks to financial institutions and customers. The project answers:

Frequency of fraudulent transactions
Differences in amounts for fraud vs non-fraud
Transaction types or locations prone to fraud
Trends over time

Dataset Description

Column	Description
Transaction_ID	-Unique ID of transaction
Customer_ID	-Unique customer ID
Transaction_Amount	-Transaction amount in currency
Transaction_Type	-Type of transaction (Credit/Debit)
Transaction_Date	-Date of transaction
Location	-Transaction location
Fraudulent	-Yes / No

Dataset contains 100 records and was manually created for educational purposes.

Tools and Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook / Google Colab

Steps Performed
Imported dataset and explored structure
Checked and handled missing values
Converted Transaction_Date to datetime
Performed EDA and visualizations:
Fraudulent vs Non-Fraudulent count
Distribution of transaction amounts
Transaction amount vs fraud status
Fraud by transaction type
Fraud distribution by location
Fraud vs non-fraud across locations
Fraud trends over time

Key Insights
Majority of transactions are non-fraudulent
Fraudulent transactions show distinct patterns in amounts
Certain transaction types have higher fraud occurrence
Fraud is concentrated in specific locations
Fraud trends vary over time

Conclusion
EDA helps detect patterns in fraudulent transactions. Insights can support fraud monitoring strategies and highlight the importance of data-driven analysis.

This project is created strictly for educational and internship purposes under Oasis Infobyte.
