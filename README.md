# PhonePe-Digital-Payments-Case-Study-Analysis
(Analyzing Transaction and Demographic Data)

Overview: This case study involves analyzing transaction data from the financial
application PhonePe along with demographic data across various states and
districts in India. The objective is to provide insights into transaction trends,
device usage, and demographic correlations, while ensuring data consistency and
performing advanced analyses to uncover deeper insights.

The datasets span multiple years and quarters, providing a comprehensive view
of transactions, user behavior, and demographic details. Participants are
expected to use their Python skills to load, explore, and analyze the data,
ultimately deriving meaningful insights and visualizations.

Dataset Details:
The data is spread across multiple sheets in an Excel file, each containing
different aspects of the transaction and demographic data. Below is an overview
of each dataset:

This case study utilizes three key datasets, each providing daily updates on
different aspects of the pandemic for various countries and regions:

. State_Txn and Users: This dataset contains transaction and user data at the
state level. It includes information on the number of transactions, total
transaction amount, average transaction value, number of registered users, and
app opens.

. State_TxnSplit: This dataset provides a breakdown of transaction types at the
state level. It includes information on different transaction types, the number of
transactions, total transaction amount, and average transaction value for each
type.

. State_DeviceData: This dataset details the device brands used by registered
users at the state level. It includes information on the number of registered
users per device brand and the percentage of users using each brand.

. District_Txn and Users: This dataset contains transaction and user data at the
district level. It includes information on the number of transactions, total
transaction amount, average transaction value, number of registered users, and
app opens for each district.

· District Demographics: This dataset provides demographic details for each
district. It includes information on the population, area, population density, and
district headquarters.

Data Dictionary:
Below is the data dictionary for the datasets used in this case study:

1. State_Txn and Users
•	State: Name of the state
•	Year: Year of the data
•	Quarter: Quarter of the year
•	Transactions: Number of transactions
•	Amount (INR): Total amount of transactions in INR
•	ATV (INR): Average transaction value in INR
•	Registered Users: Number of registered users
•	App Opens: Number of app opens

2. State_TxnSplit
•	State: Name of the state
•	Year: Year of the data
•	Quarter: Quarter of the year
•	Transaction Type: Type of transaction (e.g., Recharge & bill payments, Peer-to-peer payments)
•	Transactions: Number of transactions
•	Amount (INR): Total amount of transactions in INR
•	ATV (INR): Average transaction value in INR

3. State_DeviceData
•	State: Name of the state
•	Year: Year of the data
•	Quarter: Quarter of the year
•	Brand: Brand of the device
•	Registered Users: Number of registered users using the brand
•	Percentage: Percentage of registered users using the brand

4. District_Txn and Users
•	State: Name of the state
•	Year: Year of the data
•	Quarter: Quarter of the year
•	District: Name of the district
•	Code: District code
•	Transactions: Number of transactions
•	Amount (INR): Total amount of transactions in INR
•	ATV (INR): Average transaction value in INR
•	Registered Users: Number of registered users
•	App Opens: Number of app opens

6. District Demographics
•	State: Name of the state
•	District: Name of the district
•	Headquarters: District headquarters
•	Population: Population of the district
•	Area (sq km): Area of the district in square kilometers
•	Density: Population density
•	Code: District code
•	Alternate Name: Alternate name of the district
