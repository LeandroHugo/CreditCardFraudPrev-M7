# 🕵️ Fraud Detection Project 📈💼
![Alt text](CreditCardFraudPrev-M77/Resources/FDA1.png) 
Welcome to the **Fraud Detection Project**! In this exciting project, we apply our fresh SQL skills and data analytics to analyze historical credit card transactions and consumption patterns to identify possible fraudulent transactions. Be ready to dive into the world of fraud detection! 👀💳

## 📌 Background

Whether you are a small taco shop 🌮 or a large international business 🏢, fraud is a prevailing problem. In this project, we are going to model the data, engineer a PostgreSQL database, and finally analyze the data to find out the fraudulent trends. 👨‍💻

## 📂 Files

You can download the files necessary to get started with the project from [here](#) (link not provided).

## 🧩 Instructions

### 📊 Data Modeling

Inspect the provided CSV files and create an entity relationship diagram (ERD). A challenge here is to identify the number of tables and define the relationships among them. Quick Database Diagrams is a useful tool for creating the model.

### 🔨 Data Engineering

Utilize the database model to create a database schema for each table and relationships. Make sure to specify data types, primary keys, foreign keys, and other constraints. Once the schema is ready, import the data from the corresponding CSV files.

### 🔍 Data Analysis

We will be addressing a series of important questions to help us detect fraudulent transactions and trends.

#### Part 1: 

- Isolate and count the transactions of each cardholder that are less than $2.00.
- Identify if there's any evidence suggesting that a credit card has been hacked.
- Identify the top 100 highest transactions made between 7:00 am and 9:00 am.
- Identify if there are anomalous transactions that could be fraudulent.
- Identify if there's a higher number of fraudulent transactions made during this time frame versus the rest of the day.
- Identify the top 5 merchants prone to being hacked using small transactions.
- Create a view for each of your queries.

#### Part 2:

- Verify if there are any fraudulent transactions in the history of the two most important customers of the firm.
- Create a line plot representing the time series of transactions over the course of the year for each cardholder separately.
- Create a single line plot that contains both card holders' trend data.
- Create a box plot, representing the expenditure data from January 2018 to June 2018 for cardholder ID 25.
- Identify any outliers for cardholder ID 25.
- Identify any anomalies.

### 🚀 Challenge

Write two Python functions: one to identify anomalies using standard deviation and another to identify anomalies using the interquartile range.

## 📥 Submission

Your submission should include:

- An image file of your ERD.
- The .sql file of your table schemata.
- The .sql file of your queries.
- The Jupyter Notebook containing your visual data analysis.
- A README file containing your markdown report.
- (Optional) The Jupyter Notebook containing the optional challenge assignment.

Happy Hunting! 💼🚀
