# bigdata_project03
This project analyzed a financial data, the volatility exhibited by different companies. The technology stack leverages a suite of AWS services, encompassing Kinesis for streaming data in real time, S3 for secure data storage, Lambda for executing our code without provisioning servers, and Glue for managing our ETL jobs.

In this project, Athena is used for querying our data using SQL, while data visualization and final analysis are carried out in Jupyter Notebook.

During the execution of this project, the process starts with AWS Kinesis and Lambda being employed to collect and process the data. This data is subsequently stored in an S3 bucket. AWS Glue steps in to catalogue this data, thereby making it query-ready for Athena. The culmination of this process involves Athena's queried results being visualized in a Jupyter Notebook. This offers insights into each company's average volatility and highest daily volatility.

Visualization Questions
	1.	Which company is the most volatile?  COST
	2.	Do the findings from the second graph (Daily Highest Volatility per Company) support the conclusion from the first graph (Average Volatility Trend per Company)? 
Yes

The relationship between two visualization makes sense. If a company shows high daily volatility, it's likely to have a high average volatility as well.However, there can be some small variations due to the case of extreme volatility, which can skew the average

