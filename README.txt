Online Retailer Performance Analysis

v2020-11-18
careers@ixisdigital.com
Project Scope
• Imagine that you have been tasked with helping an online retailer measure and analyze their website’s
performance
• The retailer uses Google Analytics (GA) to track engagement and conversion on their website
• You have been given two GA datasets containing basic ecommerce metrics and asked to summarize
website performance and provide insights to help the retailer understand their website’s performance
Instructions
Datasets
• Two csv files are attached:
– sessionCounts.csv: sessions, transactions, and QTY broken out by browser * deviceCategory *
date
– addsToCart.csv: addsToCart broken out by month
Analysis
• Write an R (preferred) or Python script that produces an xlsx file with two worksheets, which would
serve as reference tables delivered with the slide deck (see below):
– The first sheet should contain a Month * Device aggregation of the data with the following metrics:
Sessions, Transactions, QTY, and ECR (= Transactions / Sessions)
– The second sheet should contain a Month over Month comparison (for the most recent two months
in the data) for all available metrics (including Adds to Cart), showing: the most recent month’s
value, the prior month’s value, and both the absolute and relative differences between them
– Note: You may calculate and include additional metrics in these tables if desired, and also produce
any additional tables that support your narrative in the slide deck
– Hint: the openxlsx package provides all the required functionality to generate xlsx files if you are
working in R
• Keep in mind: the more readable and well-documented your code is, the easier it will be for the IXIS
hiring team to evaluate your skillset
• No manual modification of the xlsx output is allowed – these tables must be generated 100% program-
matically through your script
• Your code should minimally include the following steps:
– Any data exploration and cleaning steps that you believe are appropriate
– Production of the data tables described above: show off your data wrangling/manipulation skills
here (tidyverse especially)
– Outputting the tables into separate worksheets within a single xlsx file
• Submit your code either as:
– Preferred: A link to a git repo (GitHub, Bitbucket, etc.)
1
– Alternative: A zip file emailed to the IXIS hiring manager
Client Deliverable
• Prepare a slide deck (maximum 4 slides, not including the title) that would serve as a client deliverable
for this project
– Assume the primary audience will be a non-technical marketing/UX team whose job is to improve
their retail website’s performance
– Summarize the results of your analysis, referencing specific datapoints and trends where useful
and using data visualizations appropriately
– Provide concrete next steps / action items
• A minimal theme is fine – the submission will be evaluated primarily on the quality of the narrative
and data visualizations and how effectively they communicate the project’s results to the client
• Submit this deck as a PDF
Final Submission
• When you have completed this project, send an email to the IXIS hiring manager containing the
following:
– An estimate of the hours you spent from start to finish to complete this project
∗ Note: Please limit your time spent on this project to no more than 2 working days
– Your code, attached as a zip or a link to a git repo
– Client deliverable (slide deck), attached as a PDF