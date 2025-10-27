# Project-on-Fraud-Detection
A data analytics project focused on detecting fraudulent financial transactions using Python, SQL, Excel, and Power BI.

**Project Overview**
This project simulates a real-world financial fraud detection scenario for a credit card provider.
The goal was to detect unusual or suspicious transactions using a hybrid workflow combining Excel, SQL, Python, and Power BI — reflecting how financial institutions integrate data analytics, business intelligence, and reporting for fraud risk monitoring.

**Tools & Technologies**
Tool     -  Purpose
Excel	   - Data cleaning, derived features, and pivot-based exploratory analysis
SQL (MySQL) -	Data validation, transactional queries, and business insights
Python	- Data preprocessing, analysis, and anomaly detection logic
Power BI	-Interactive dashboards for fraud visualization and reporting

**Project Workflow**
1. Excel – Data Foundation
Cleaned and formatted the dataset for analysis.
Created derived features: transaction amount categories, transaction time (hour, day, month), and days since last transaction.
Built pivot tables and charts for early trend analysis and outlier detection.

2. Python – Analytical Processing
Imported and preprocessed cleaned data (handled missing values, standardized data types).
Performed exploratory data analysis using Pandas and Matplotlib.
Computed summary metrics and flagged suspicious transaction patterns based on frequency and amount variations.

3. SQL – Business Insights
Analyzed over 2,500 transactions to identify spending trends and outlier behavior.
Extracted insights such as:
Debit transactions > Credit transactions
ATM transactions had the highest average value
Fort Worth was the busiest transaction hub
Portland showed unusually high transaction amounts
High login attempts correlated with high-value transactions
Generated business summaries that were later visualized in Power BI.

4. Power BI – Fraud Monitoring Dashboard
Designed an interactive dashboard summarizing fraud-related KPIs:
Total Transactions
Total Amount
Distinct Accounts
Percentage of Flagged Transactions
Visualized:
Transaction volume by channel and location
Occupation-wise spending and account balances
Anomaly trends over time (heatmaps and summary tables)
High-value flagged transactions for monitoring

**Key Insights**
Students generated the highest number of transactions, while Doctors maintained the largest account balances.
Fort Worth was the most active location, whereas Portland exhibited high-value suspicious activity.
ATM transactions showed the highest average amounts, signaling a potential fraud-prone zone.
High login attempts combined with large transaction amounts emerged as strong fraud risk indicators.

**Learning Outcomes**
Developed an end-to-end fraud detection workflow integrating Excel, SQL, Python, and Power BI.
Enhanced ability to analyze, validate, and visualize large financial datasets.
Strengthened practical skills in data-driven storytelling and business communication.
Learned to bridge technical analytics and business insights for fraud prevention strategies.
Improved ability to explain fraud detection findings to both technical and business stakeholders
