# Bank-Transaction-Analysis
## Project Demo
[Watch the project walkthrough on LinkedIn](https://www.linkedin.com/posts/udokanma-anthony-nyenke-99864b412_python-dataanalysis-pandas-activity-7496556885328904192-v7g_?utm_medium=ios_app&rcm=ACoAAGkaO8QBPiadmsQcNs6YyXb4qds1reLdTbk&utm_source=social_share_send&utm_campaign=copy_link)

# Banking Transactions Analysis

**Tools:** Python (Pandas, NumPy, Matplotlib) | Jupyter Notebook

## Project Overview
This project is an exploratory data analysis of 60,005 banking transactions across 10 regions in Nigeria. It looks at how transactions vary by region, channel, product category, transaction type, status, and month, and turns the findings into clear business insights.

## Objectives
- Clean and prepare raw transaction data for analysis
- Identify the highest performing regions and channels
- Compare credit and debit activity
- Measure transaction success, pending, and failure rates
- Find the busiest months and the regions that generate the most fees

## Data Cleaning
- Removed 5 duplicate records
- Excluded 8 transactions with missing Amount values. They were not filled with averages because that would create inaccurate financial records.
- Labeled 16 missing transaction statuses as "Unknown"
- Standardized inconsistent text entries (e.g. "lagos" to "Lagos", " mobile app " to "Mobile App")
- Corrected an inconsistent date format
- Final dataset: 59,992 clean records

## Key Insights
- **Total transaction value:** about 75.34 billion
- **Top region:** Lagos led with about 7.75 billion in transactions
- **Most used channel:** Mobile App
- **Credit vs debit:** almost evenly split (30,069 credit and 29,923 debit)
- **Transaction status:** about 80% successful, with roughly 10% pending and 10% failed
- **Busiest month:** March, with 5,226 transactions
- **Fees generated:** about 754.9 million in total, with Lagos the highest fee-generating region

## Visualizations
- Bar chart of transaction value by region
- Chart of transaction activity by month
- Column plot of channel usage
- Pie chart of transaction statuses

## Conclusion
Most transactions were completed successfully, which shows a reliable payment system. Customers preferred the Mobile App channel, activity changed from month to month, and a few regions contributed more in transaction value and fees than others.

## Skills Demonstrated
Data cleaning, handling missing values, groupby aggregations, date feature engineering, data visualization, and business insight writing.

## Author
**Udokanma Anthony Nyenke**
Data Analyst | Excel, Power BI, SQL, Python, Tableau
GitHub: [UdokanmaNyenke](https://github.com/UdokanmaNyenke)
