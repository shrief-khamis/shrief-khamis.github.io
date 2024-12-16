## Portfolio

---

### Exploratory Data Analysis

[Online retail Store](https://github.com/shrief-khamis/online-retail-eda)

Exploring data from an online retail store based in the UK using Python (Jupyter Notebook):
* Presented my process for identifying the key variable to understand the data.
* Cleaned the data, by removing erroneous records and isolating transaction classes like discounts and returns.
* Analyzed the data, and presented the results through visualizations.
* Provided actionable suggestions related to the data structure, the data entry process, discount policy, return rate, and losses.

A real-life application for a project like that would be in a situation where a company acquires an online store and inherits its books without much information about the data entry process or the data structure.

---
### ELT Data Pipeline

[ELT Pipeline](https://github.com/shrief-khamis/elt-pipeline)

A pipeline where I **Extract** the data with a Lambda function written in Python, **Load** the data into a staging table inside the database, and **Transform** the data into a normalized form using PostgreSQL functions and triggers.
* **EC2**: a temporary instance to run a Python script to generate mock data and place it in an S3 bucket.
* **S3**: Acts as a data lake here.
* **RDS**: a PostgreSQL database ready for OLTP workload, initiated and configured with a staging table, a set of related tables in a star schema, and a function to transform/normalize the data that gets triggered with inserts into the staging table.
* **Lambda**: a serverless function that gets invoked with every file uploaded to the S3 bucket, and takes the its contents, connects to the database, and insert the contents into the staging table.

---
[European Soccer database](https://github.com/shrief-khamis/exploring-european-soccer-database)

A fun project where I used PostgreSQL to explore the European Soccer Database.
I wrote queries to summarize some information and comparisons about all the leagues in the database and provide more in-detail summaries about specific leagues, using some advanced SQL techniques like **Window functions** and **Subqueries**.
A real-life application for this would be in any website or application that is interested in presenting any of the European leagues' results and stats in any manner they see best.

---
### Visualization

[Excel Sales Dashboard](https://github.com/shrief-khamis/sales-excel-dashboard)

A project where I cleaned and formatted some raw sales data, made some calculations and pivot tables, then used these to create an interactive dashboard presenting key information about the sales data.

<img src="images/excel_dashboard.png?raw=true"/>

---
[Power BI Call Center Dashboards](https://github.com/shrief-khamis/call-center-powerbi-dashboards)

Two projects where I used Power BI, Power Query, DAX to create two Dashboards to present performance overview of call centers

The first:

<img src="images/powerbi_dashboard1.png?raw=true"/>

The second:

<img src="images/powerbi_dashboard2.png?raw=true"/>

---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
