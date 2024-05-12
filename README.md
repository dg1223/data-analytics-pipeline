# Data Analytics Pipeline

*If the image does not open directly, please click on the README.md file and open it from there.
![image](https://github.com/dg1223/data-analytics-pipeline/assets/4992116/2ed2c2cb-d545-4747-98cc-8f7478b4f9e0)

This is a data analytics pipeline for business intelligence related tasks that I created at Openhaus.

It is an end-to-end automated pipeline built on Amazon Web Services that does the following every day:
1.  Turns on the analytics server on Production.
2.  Collects data from production database at 8 am.
3.  Runs SQL query on updated production data (existing + new) to generate daily customer engagement metrics.
4.  Populates an analytics dashboard for the business team based on new customer engagements.
5.  Sends an email to business and product teams with the updated dashboard as well as a spreadsheet containing only new engagements.
6.  Turns off the analytics server when job is finished.

# Cost Reduction
This pipeline cost the company only $4.03 per month to process data on 3000 users which was the cheapest compared to what other available products in the market were offering at that time.
Below is a comparison:
- My solution: $4.03
- IBM: $10.00
- Microsoft: $20.00
- Amazon: $27.00
- Tableau: $70.00
