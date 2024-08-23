# Data Analytics Pipeline

*If the image does not open directly, please click on the README.md file and open it from there.
![image](https://raw.githubusercontent.com/dg1223/data-analytics-pipeline/main/BI-pipeline-AWS.png)

This is the first data analytics pipeline that I created at Openhaus.

It is an end-to-end automated pipeline built on Amazon Web Services that does the following every day:
1.  Turns on the analytics server on Production.
2.  Collects data from production database at 8 am.
3.  Runs SQL query to collect incremental updates from the production and generates daily customer engagement metrics.
4.  Populates an analytics dashboard for the business team to show new customer engagements.
5.  Sends an email to business and product teams with the updated dashboard as well as a spreadsheet containing only new engagements.
6.  Turns off the analytics server after job is finished.

